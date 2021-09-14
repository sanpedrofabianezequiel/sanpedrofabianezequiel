## Hide frames

You can hide the frames around the trophies.  
`Available value: boolean type (true or false)`  
`Default: no-frame=false`

```
https://github-profile-trophy.vercel.app/?username=sanpedrofabianezequiel&no-frame=true
```

<p align="center">
  <img width=660 src="https://user-images.githubusercontent.com/6661165/104810887-1d21c800-583b-11eb-8f0d-785c1640dc5d.png">
</p>


# Contribution Guide

## Environment

* Deno >= v1.9.2
* [Vercel](https://vercel.com/)
* GitHub API v4

## Local Run

Create `.env` file to project root directory, and write your GitHub token to the `.env` file.
Please select the authority of `repo` when creating token.

```
GITHUB_TOKEN=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

Run local server.

```
deno run --allow-net --allow-read --allow-env debug.ts
```

Open localhost from your browser.


## Editor config

Read the [.editorconfig](./.editorconfig)

## Run deno lint

If you want to contribute to my project, you should check the lint with the following command.

```
deno lint --unstable
```

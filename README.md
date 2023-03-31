# Project Setup with Perforce

## Setup Tailscale

- [Download Tailscale](https://tailscale.com/download/)
- Login with the Google Account
- Remember to open tailscale before working on UE

## Setup Perforce Helix Core

- [Download p4v client](https://www.perforce.com/downloads/helix-visual-client-p4v)
- Go through the setup steps
- On connection page use server - `ssl:hogwarts:1666` and user - `nabil`
- Watch https://www.youtube.com/watch?v=Hvmvv2MG-UE
- Open terminal and enter this command

    ```console
    p4 set P4IGNORE=.p4ignore
    ```

- Create a new workspace and get latest revisions

## Setup Perforce in Unreal Engine

- Open the project from the cloned perforce directory
- Click on `Source Control` and setup with server - `ssl:hogwarts:1666`, user - `nabil` and the workspace you setup previously

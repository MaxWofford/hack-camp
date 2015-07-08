# Portfolio

## Cloud9

- Go to https://c9.io, click the `Sign Up` button, and create an account
- Click `Go to your dashboard`
- Creating a workspace
    - Click `Create a new workspace`
    - Give it the name `hack-camp`
    - Make sure the `Custom` type is selected
    - Click `Create workspace`
- Configuring your workspace
    - Select the `Minimal Editor` preset.
    - Change `Soft Tabs` to 2
    - Turn on `Enable Auto-Save`
    - At the very top of the window, click the little triangle on the bar to show the Cloud9 editor options.

      ![](img/c9_configuring_workspace_top_bar.png)

    - Click `View` and then `Console` to open up the terminal
    - Your workspace should now look like the following:

      ![](img/c9_configured_workspace.png)

    - Go ahead and close the welcome tab

      ![](img/c9_closed_welcome_tab.png)

    - Final step, paste the following command into the terminal on the bottom and hit enter. This may take a few minutes to finish.

            $ curl -sL https://git.io/vtbp6 | sudo dd of=/usr/local/bin/live_reload && sudo chmod +x /usr/local/bin/live_reload && live_reload

    - When it's done, your workspace should look like the following

      ![](img/c9_live_reload_installed.png)

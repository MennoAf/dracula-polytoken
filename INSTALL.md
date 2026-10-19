### [Polytoken](https://docs.polytoken.dev)

#### Install using Git

If you are a Git user, you can install the theme and keep it up to date by cloning the repo:

```bash
git clone https://github.com/dracula/polytoken.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/polytoken/archive/refs/heads/main.zip) option and unzip it.

#### Activating theme

1. Copy `dracula.yaml` into your Polytoken user themes directory:

   ```bash
   mkdir -p ~/.config/polytoken/themes
   cp dracula.yaml ~/.config/polytoken/themes/dracula.yaml
   ```

   If you set a custom `XDG_CONFIG_HOME`, use `$XDG_CONFIG_HOME/polytoken/themes/` instead.

2. Set the theme in your Polytoken config file:

   ```toml
   tui.theme-file = "dracula"
   ```

   Or preview it for the current session by running `/theme dracula` inside Polytoken.

3. Boom! It's working ✨

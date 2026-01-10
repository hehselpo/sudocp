```nix
{ pkgs, ... }:

let
  who = {
    name = "kemal";
    handle = "kewwwal";
    status = "unemployed";
  };
in {
  env = {
    os = "arch";
    wm = pkgs.niri;
    sh = pkgs.fish;
    term = pkgs.kitty;
  };

  stack = {
    langs = with pkgs; [
      lua
      python3
      bash
    ];

    tools = with pkgs; [
      git
      docker
      ngrok
      vscode
    ];
  };

  social = {
    discord = 477420583915618304;
    github = "https://github.com/kewwwal";
  };
}
```
<div align="center">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kewwwal/kewwwal/output/github-contribution-grid-snake-dark.svg" />
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kewwwal/kewwwal/output/github-contribution-grid-snake.svg" />
<img alt="github-snake" src="https://raw.githubusercontent.com/kewwwal/kewwwal/output/github-snake.svg" />
</picture>
</div>

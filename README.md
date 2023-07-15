# flaky.town

```
               ___         _____      ___
              /   \        \    \    /   |
              \    \        \    \  /   /
               \    \        \    \/   /
           _____\    \_______ \       /
          /                  \ \     /       /\
         /____________________\ \    \      /  \
               _____             \    \    /    \
              /    /              \    \  /    /
             /    /                \   / /    /
            /    /                  \ / /    /______
           /    /    ------------    v /            \
  ________/    /     |flaky.town|     /    _________/
 /            / \    ------------    /    /
 \______     / / \                  /    /
       /    / /   \                /    /
      /    /  \    \              /____/
     /    /    \    \  ______________________
     \   /      \    \ \                    /
      \ /       /     \ \_______     ______/
       v       /       \        \    \
              /   /\    \        \    \
             /   /  \    \        \    \
            /   /    \    \        \___/
            \__/      \____\

```

# What is this?

This is the system configuration for [flaky.town](https://flaky.town), a NixOS-based tilde server.

# Planned Services

| Software          | Description                 | Language | URL                                         | Notes |
| :---------------- | :-------------------------- | :------- | :------------------------------------------ | :---- |
| static-web-server | Static HTTP Server          | Rust     | [website](https://static-web-server.net/)   |       |
| agate             | Gemini server               | Rust     | [github](https://github.com/mbrubeck/agate) |       |
| gotify            | push notifications          | Go       | [website](https://gotify.net/)              |       |
| conduit           | matrix server               | Rust     | [website](https://conduit.rs/)              |       |
| nginx?            | reverse proxy / HTTP server | C        | [website](https://www.nginx.com/)           |       |

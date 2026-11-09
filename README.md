
[README.md](https://github.com/user-attachments/files/34581973/README.md)

[SNAKE_OPTIONAL.md](https://github.com/user-attachments/files/34581976/SNAKE_OPTIONAL.md)# Optional contribution snake

1. Add `.github/workflows/snake.yml` to the `khaoulaBloom/khaoulaBloom` repository.
2. In repository Settings > Actions > General, ensure Actions are enabled and workflow permissions permit writing repository contents (if required by your repository settings).
3. In Actions, run **Generate contribution snake** using **Run workflow**.
4. Confirm that the `output` branch contains `github-contribution-grid-snake.svg`.
5. Then insert this snippet under the GitHub analytics section in README.md:

```html
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/khaoulaBloom/khaoulaBloom/output/github-contribution-grid-snake-dark.svg" />
    <img alt="Animated contribution snake" src="https://raw.githubusercontent.com/khaoulaBloom/khaoulaBloom/output/github-contribution-grid-snake.svg" width="790" />
  </picture>
</div>
```

Do not insert the snippet until the workflow has successfully generated the assets, or the image will appear broken. The snake is optional; the main README works without it.

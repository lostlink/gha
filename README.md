# Reusable Github Actions

Example:

```
linters-phpstan:
  name: Linters
  uses: lostlink/gha/.github/workflows/phpstan.yml@main
  secrets:
    VAPOR_API_TOKEN: ${{ secrets.VAPOR_API_TOKEN }}
```

More Info coming soon...
# mkdocs-material-tutorial
Create document site with MkDocs Material

# Deploy to Netlify

Create file `netlify.toml` with the following content.
```sh
# netlify.toml
[build]
  command = "mkdocs build"
  publish = "site"
```

Create file `requirements.txt` to specify the version of MkDocs Material.
```sh
mkdocs-material==9.4.1
```

Create file `runtime.txt` to specify the Python version.
```sh
3.8
```

# References

- [Deploy MkDocs to Netlify](https://www.starfallprojects.co.uk/projects/deploy-host-docs/deploy-mkdocs-material-netlify/)
Ejecuta el comando `mvn --batch-mode deploy` para publicar a {% data variables.product.prodname_registry %}. La variable de ambiente `GITHUB_TOKEN` se configurará con el contenido del secreto `GITHUB_TOKEN`. {% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@3.1" or currentVersion == "github-ae@next" %}La clave de `permissions` especifica el acceso otorgado al `GITHUB_TOKEN`.{% endif %}
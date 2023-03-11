## Steps to setup the environment
```bash title="CLI commands"

# Create a new virtuale env
python -m venv venv

# Actiavte the virtual env
.\venv\Scripts\activate

# Install the mkdocs material library
pip install mkdocs-material

# Create a new site
mkdocs new .

# Publish the site
mksdocs serve

#Update the theme to mkdocs from default in mkdocs.yml

# Does a github push to remote repository
mkdocs gh-deploy

```
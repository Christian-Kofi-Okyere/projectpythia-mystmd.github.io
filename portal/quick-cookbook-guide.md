# MyST Cookbook Contributing Guide Notes

For a more detailed, step-by-step contributor guide, see the **Full Cookbook Contributor's Guide**
<p style="text-align: center; margin-top: 2em;">
  <a href="cookbook-guide.md" style="display: inline-block; background-color:rgb(13, 83, 130); color: white; padding: 8px 10px; font-size: 1.1em; border-radius: 8px;">
    Full Cookbook Contributor's Guide &rightarrow;
  </a>
</p>


---
## Create Repository Using Template

1. Navigate to [projectpythia/cookbook-template](https://github.com/projectpythia/cookbook-template)
2. Click **"Use This Template"** → **"Create a new repository"**

### On the next page:
- Check **"Include all branches"**
- You are the **owner**
- Create your repository name (should end with `-cookbook`)
- Select to keep it **Public**
- Then click **"Create repository"**


---

## Update Content

Follow [Git/GitHub best practices](https://foundations.projectpythia.org/foundations/getting-started-github.html) with your collaborators:

- Add content with your scientific insight as `.ipynb` files in the `notebooks/` folder  
- Update `environment.yml` to include all necessary packages  
- Update **thumbnail** to visually represent your work  
- Update `README.md` to reflect:
  - Title  
  - Description  
  - Motivation  
  - Authors  
  - Content structure  

- Update `myst.yml` with:
  - Title  
  - GitHub link  
  - Tags  
  - Keywords (clarify the difference!)  
  - Table of contents (`toc`)  
  - Jupyter &rarr; Binder &rarr; Repo links  

- Update `CITATION.cff` with:
  - Authors’ names, ORCID, website, and affiliation  
  - Title  
  - Abstract  

---

## Ready to Publish?

1. Make sure you’re added to the `ProjectPythia` organization  
2. From **repository settings**, transfer the repo to the `ProjectPythia` organization  
3. Open a PR editing `cookbook_gallery.txt` with your repo name in the [Cookbook Gallery Repository](https://github.com/projectpythia/cookbook-gallery)  
4. Await review  
5. Someone from the Pythia team will publish a **citable release**

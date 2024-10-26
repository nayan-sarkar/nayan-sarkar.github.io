# Personal Website Portfolio

## Run Project Locally
- Install jekyll (https://jekyllrb.com/docs/)
- In terminal inside Project Directory `bundle install`
- In terminal `bundle update`
- In terminal `bundle exec jekyll serve`

## Instructions
1. Modify site-wide configurations to match your requirements from `_config.yml`.
2. Upload any files (e.g pdf, zip etc.) to **files/** directory. These files will appear at https://[your-github-username].github.io/files/example.pdf.
3. To change the site avatar/logo, add your avatar in **assets/images** directory. Modify `_config.yml` to reflect your avatar's filename in `avatar-filename` variable.
```
avatar-filename: <yourFileName.jpg>
```
4. Replace **assets/favicon.png** with your own favicon.
5. To change site contents, add/modify files in different collection's directories.
  - Experience: Add/modify the contents from **_experiences** directory.
  - Education: Add/modify the contents from **_education** directory.
  - Skills: Add/modify the contents from **_skills** directory.
  - Projects: Add/modify the contents from **_projects** directory.
  - Publications: Add/modify the contents from **_publications** directory.
  - Certifications: Add/modify the contents from **_certifications** directory.
  - Achievements: Add/modify the contents from **_achievements** directory.
6. To add/modify blog posts, modify the contents in **_posts** directory. Follow the given filename structure for blog post e.g. `YYYY-MM-DD-my-post-title.md`.
7. After github pages deployment, your site will be available at `your-github-username.github.io`

## Adding Google Analytics Tracking
- Login to [Google Analytics](https://analytics.google.com/) and create a new property to receive a Tracking ID for your website.
- Edit your `_config.yml` of github, make sure it contains following content:
```
google_analytics: UA—XXXXXXXX-X
```
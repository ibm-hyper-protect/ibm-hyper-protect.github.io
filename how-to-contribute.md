# How to Contribute

## Live Site
- [https://ibm-hyper-protect.github.io](https://ibm-hyper-protect.github.io)
- This site is externally accessible and widely distributed for promoting Hyper Protect services in the User / Developer community
- All information - videos, code-samples, blog posts, wiki-articles shared on this web-site must be approved for External use. Do not share:
  - Anything marked as "IBM Confidential"
  - Information about Projects that are in development without prior approval
  - Architecture diagrams without prio approval
- This website is sourced by a **GitGub Repo**
  
## GitHub Repo
- https://github.com/ibm-hyper-protect/ibm-hyper-protect.github.io
- Write / Merge access is shared by:
  - [Chris Poole](chrispoole@uk.ibm.com)
  - [Sandeep Batta](sbatta@us.ibm.com)

### Repo Structure
- [index.html](./index.html) - Landing Page for Hyper Protect
- [fss.html](./fss.html) - Landing Page for FSS - Financial System Services
- [_data/blogs.yml](./_data/blogs.yml) - list of `blog posts` to be shared on this website
- [_data/code-patterns.yml](./_data/code-patterns.yml) - list of `code-patterns` to be shared on this website
- [_data/podcasts.yml](./_data/podcasts.yml) - list of `podcasts` to be shared on this website
- [_data/tech-talks.yml](./_data/tech-talks.yml) - list of `tech-talks` to be shared on this website
- [_data/tutorials.yml](./_data/tutorials.yml) - list of `tutorials` to be shared on this website
- [_data/videos.yml](./_data/videos.yml) - list of `videos` to be shared on this website


### How to Update the website on github.com
  1. Update the required files according to the structure mentioned above
    - if structural changes are requried, confer with the Repo Owners
  1. Click on `Propose File Change`
  1. Click on `Create Pull Request`
  1. Alert the Admins to check the Pull Request and `Merge` the update

### How to Update the website using a Local Repo?

1. Setup your local environment
  - Create an ID on [github.com](https://github.com) and request access for https://github.com/ibm-hyper-protect
  - [Install the required packages, viz. `ruby`, `gem`, etc.](https://jekyllrb.com/docs/installation/)
  - Clone the Repo
  ```
  > mkdir ibm-hyper-protect
  > cd ibm-hyper-protect
  > git remote add origin git@github.com:<your-id>/ibm-hyper-protect
  > git pull origin master
  ```
  - `gem install jekyll bundler`

1. Update the Required file
1. Create a `Pull Request`
1. Run: `bundle exec jekyll serve`
1. Go to [localhost:4000](http://localhost:400)

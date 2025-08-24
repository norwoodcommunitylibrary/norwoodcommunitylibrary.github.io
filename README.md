# norwoodcommunitylibrary.github.io

## Purpose

This is the simple static page for the Norwood Community Library, in order to
link to other pages or to share some resources in a central location. Owned by
Brandon Montes, maintained (for now) by Justine.

## How to Use

[norwoodcommunitylibrary.github.io](https://norwoodcommunitylibrary.github.io)

To run locally:
- Launch wsl
- `cd /mnt/wsl/norwoodcommunitylibrary.github.io`
- `bundle exec jekyll serve`

Deployment is simply pushing to main. Can deploy from a branch instead under Settings > Pages > Build and deployment

## Debugging Tips

- delete cache for the website
- ssh-agent bash -c 'ssh-add ~/.ssh/id_rsa_ncl; git push'

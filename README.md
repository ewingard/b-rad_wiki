# B-RAD Lab Wiki Page

Live page: https://ewingard.github.io/b-rad_wiki/ (for now)

## Notes for future maintainers
* Use [Github markdown](https://guides.github.com/features/mastering-markdown) to create pages. All content will be converted into a website format upon pushing a commit. Please ensure any links/content are in their respective folders and up-to-date prior to pushing.
* It usually takes few minutes for a pushed commit to go live. To edit and view locally, use Jekyll (instructions below).

### To run the site locally on your laptop
* Install Jekyll following the instruction: https://jekyllrb.com/docs/installation/. (See [here](https://jekyllrb.com/docs/installation/macos/) for mac)
* Clone the repository: ``git clone https://github.com/ewingard/b-rad_wiki.git; cd b-rad_wiki``
* Run ``bundle install`` to download theme and its dependencies
* Run ``bundle add webrick``
* Run ``bundle exec jekyll serve`` and the site should be live at http://localhost:4000/
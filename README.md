### Jekyll Commands
#### Launch new site
jekyll new . --force

#### Serve locally
bundle exec jekyll serve

to test baseurl

bundle exec jekyll serve -b /shacl-patterns

to fix dependencies: 
    bundle update && bundle install
    
    then 
    
    bundle add webrick
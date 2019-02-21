# README

This is a vanilla, out-of-the-box implementation of Hyrax 2.4.1 See https://github.com/samvera/hyrax for more details.

- git clone https://github.com/IUBLibTech/vanilla-hyrax241.git
- bundle install
- rake db:migrate
- bin/rails hydra:server (continues running)
- bin/rails hyrax:default_admin_set:create
- open http://localhost.3000

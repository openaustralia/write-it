require "capistrano/setup"
require "capistrano/deploy"
require "capistrano/defaults"
require "capistrano/git"
require "capistrano/django"

role :web, "deploy@127.0.0.1:2200"

set :application, "write-it"
set :scm, :git
set :repo_url, "https://github.com/ciudadanointeligente/write-it.git"
set :django_settings_dir, "writeit/settings"
set :pip_requirements, "requirements.txt"
set :keep_releases, 5
set :nginx, true
set :deploy_to, "/srv/write-it"
set :wsgi_file, "writeit/wsgi.py"
set :stage, :production
set :django_settings, "production"
set :shared_virtualenv, true

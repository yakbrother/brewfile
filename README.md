/* Brewfile for backup purposes */

tap "homebrew/bundle"
tap "homebrew/cask"
tap "homebrew/core"
tap "homebrew/services"
brew "apr-util"
brew "python@3.11"
brew "awscli"
brew "openldap"
brew "curl"
brew "freetds"
brew "libpq"
brew "php"
brew "composer"
brew "dnsmasq"
brew "helix"
brew "hugo"
brew "libfido2"
brew "lua"
brew "mackup"
brew "mysql"
brew "mysql@5.7", restart_service: true
brew "nginx"
brew "node"
brew "redis", restart_service: true
brew "starship"
brew "yarn"
cask "chromium"
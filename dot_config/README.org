* Dotfiles
  This is my dotfiles configuration, to be able to use this you will need to the use the following tools [[https://github.com/twpayne/chezmoi/][chezmoi]] and [[https://getantibody.github.io/install/][antibody]]
** Setup
1. Install chezmoi: ~brew install twpayne/taps/chezmoi~
2. Install antibody: ~brew install getantibody/tap/antibody~
3. Install git
4. Run: ~chezmoi init https://github.com/username/dotfiles.git~
5. Update: ~chezmoi apply~
** Keeping up to date
Use chezmoi to upgrade itself: ~chezmoi upgrade~
Then: ~chezmoi update~

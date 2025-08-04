# Karabiner Elements Config

## Installation process
1. Download karabiner elements from [official website](https://karabiner-elements.pqrs.org/)
2. Install the package
3. Clone the repository
   ```bash
   git clone git@github.com:totsamyroma/karabiner-conf.git
   ```
4. Remove default karabiner config
   ```bash
   rm ~/.config/karabiner/karabiner.json
   ``` 
5. Create a symlink to the cloned repository
   ```bash
   ln -s ~/path/to/karabiner-conf/karabiner.json ~/.config/karabiner/karabiner.json
   ```

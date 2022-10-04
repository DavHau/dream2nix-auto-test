This repo serves the purpose of testing dream2nix.

Its flake contains package sets generated automatically by dream2nix.  
- Each package set contains the most popular packages for each ecosystem.  
- Each package set lives on its own branch prefixed with `pkgs-`.  
- The package sets are updated by a bot daily.  

To see which packages fail to build, navigate to one of the `pkgs-...` branches and click on the hercules-ci action.  

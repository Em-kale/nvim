##NOTE - this repo is deprecated, I have since switched to a config based on kickstart to leverage lazy.nvim and ease of implementation 


Just my personal Nvim configuration - includes LSP, fuzzyfinder, undo tree, pretty colours, etc. 

Note: as of March 2024, you must use the recent, unstable version of nvim or it will explode 
    - to install on ubuntu, you cannot use apt, as it is outdated, snap has an updated version that will do though. 

You must then install packer by cloning the repository into your nvim path. Just navigate to the packer repo, it is like the first thing in the readme. 
Then navigate to the packer file and in the vim command console enter
```so```

```PackerSync```

Other things you will need to install manually as of now to get this working:

    - npm 
    - prettier, if you want it (via npm) 
    - ripgrep
    - packer

May need to run :TSUpdate if getting weird errors upon opening files with odd file extensions 

On WSL 
 - Need to install gcc, libc6-dev, and unzip. 

Orginally based on the primeagen's nvim 0 to LSP guide (though it drifts, and the LSP configuration is probably entirely different).


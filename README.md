# Back_To_Nvim
It could be helpful if you have some Vim experience before. Heard Nvim is getting hot. And wanna try it out. 
Honestly, those motion key combos makes you feel like playing street fighters while coding. 

Bad part is I am so used to press ESC while finish editing something. 

While writing some descriptions on PR, while editing a sent message on discord, GG!

# The Vim I know was like this. 
![image](https://github.com/zkrguan/Back_To_Nvim/assets/97544709/26518c87-0fee-48ec-b204-a7be3d868fbd)

# If you are a rookie like me from 2023/08 who only use vim to change files on the deployment server directly.
Try the kickstart-nvim. So nice. Literally so easy. 
## Around Aug 28th 2023, set up with all the default setting. 
```
1. The link to kickstart nvim
https://github.com/nvim-lua/kickstart.nvim.

If you don't have a .config repo inside your home.
2. mkdir -p ~/.config/vim

3. cd ~/.config/vim

4. nvim init.lua

5. copy and paste whatever inside the kick start vim init.lua

6. start your nvim, and all the plugins will be installed

7. nvim inside your working repo

8. space + sf and this is like a magic

```
Looks better than you thought right? Pretty fun to use with. 
![image](https://github.com/zkrguan/Back_To_Nvim/assets/97544709/af557a14-f248-4075-b1d3-9de45f68b34c)

## Sept 4th, 2023, Added NvimTree into the Nvim. 
```
1. I decided to separate the plugin and keymaps like the other advanced users did.
2. Every time add a new plug into, nvim plugInName.lua inside the lua/plugins dir.
3. To whomever use the WSL or WSL2, don't be another me.
    **On windows.**
    download the nerdfont https://www.nerdfonts.com/font-downloads
    unzip
    double click the ttf file,
    install

    Open your terminal( anyone is fine, does not have to be WSL)
    Left side profile-> Defaults
    Right panel -> Appearance
    Choose nerd font and save.
    Reopen your WSL and then nvim    
```
After nvim tree, this is how it looks. It is better than I expected. 
![image](https://github.com/zkrguan/Back_To_Nvim/assets/97544709/d3c8d580-6618-45da-8dfe-0cf07e2a03ac)


# NVim after I customized.
Still Trying out. Will keep updating this repo. 


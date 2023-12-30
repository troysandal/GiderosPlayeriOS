# Export Gideros Player Doesn't Support Lua Debugging.
This project was exported from an empty Gideros Project that had the Flurry and StoreKit plugins added.  It uses [GitLFS](https://git-lfs.com/) for the `*.a` libraries. 

Once running open the "Gideros Studio/Examples/Graphics/Bird Animation" project in Gideros Studio, set a breakpoint on line 10 of bird.lua `Bird:init()` then press Player -> Debug.  No breakpoint will be hit.  If you do the same thing using the pre-packaged Gideros iOS Player you will hit a breakpoint.

```
package com.connorl.friends;
 
        import org.bukkit.entity.Player;
        import org.bukkit.plugin.java.JavaPlugin;
 
        import java.util.HashMap;
 
/**
 * Created by Connor on 30/10/2014.
 */
public class Main extends JavaPlugin {
    public Player pla = null;
    public HashMap<Player req, Player pla> requests = new HashMap<Player req, Player pla>();
 
    @Override
    public void onEnable() {
        saveDefaultConfig();
    }
 
 }
```

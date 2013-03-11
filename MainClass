package Grovesy101Mod;

import net.minecraft.block.*;
import net.minecraft.creativetab.CreativeTabs;
import net.minecraft.item.*;
import net.minecraftforge.client.MinecraftForgeClient;
import net.minecraftforge.common.EnumHelper;
import Grovesy101Mod.Blocks.*;
import Grovesy101Mod.Containers.*;
import Grovesy101Mod.Guis.*;
import Grovesy101Mod.Items.*;
import Grovesy101Mod.TileEntities.*;
import cpw.mods.fml.common.Mod;
import cpw.mods.fml.common.Mod.Init;
import cpw.mods.fml.common.Mod.Instance;
import cpw.mods.fml.common.Mod.PostInit;
import cpw.mods.fml.common.Mod.PreInit;
import cpw.mods.fml.common.SidedProxy;
import cpw.mods.fml.common.event.FMLInitializationEvent;
import cpw.mods.fml.common.event.FMLPostInitializationEvent;
import cpw.mods.fml.common.event.FMLPreInitializationEvent;
import cpw.mods.fml.common.network.NetworkMod;
import cpw.mods.fml.common.network.NetworkMod.SidedPacketHandler;
import cpw.mods.fml.common.network.NetworkRegistry;
import cpw.mods.fml.common.registry.GameRegistry;
import cpw.mods.fml.common.registry.LanguageRegistry;

@NetworkMod(clientSideRequired = true, serverSideRequired = false)
@Mod(modid = "Grovesy RPG", name = "GrovesyRPG", version = "0.0.1")
public class MainClass {
  @SidedProxy(clientSide = "Grovesy101Mod.ClientProxy", serverSide = "Grovesy101Mod.CommonProxy")
		public static CommonProxy proxy;
	
	public static CreativeTabs GrovesyTab = new GrovesyTab(CreativeTabs.getNextID(), "Grovesy Tab");
	
		
	public GuiHandler guiHandler = new GuiHandler();
	
	
	//Block Declaration\\\\\\\\\\\
	
	
	
	//Item Declaration\\\\\\\\\\\\
	
	
	
	//Enums\\\\\\\\\\\\\\\\\\\\\\\
	
	public static EnumToolMaterial ToolMaterial = EnumHelper.addToolMaterial
			("Material Name", 3, 64, 10.0F, 3, 15);

	public static EnumArmorMaterial ArmourMaterial = EnumHelper.addArmorMaterial
			("Material Name", 24, new int[] { 2, 5, 3, 2 }, 16);
			
		
	@PreInit
	public void load(FMLPreInitializationEvent preEvent){
		MinecraftForgeClient.preloadTexture("PATHTOBLOCKFILE.png");
		MinecraftForgeClient.preloadTexture("PATHTOITEMFILE.png");
	}
	
	@Init
	public void load(FMLInitializationEvent Event){
		
		NetworkRegistry.instance().registerGuiHandler(this, guiHandler);
				
		//Block Defining\\\\\\\\\\
		
		
			//GameRegistry\\\\\\\\\\\\
			
			
			//LanguageRegistry\\\\\\\\
				
				
		//Item Defining\\\\\\\\\\\
			
				
			//GameRegistry\\\\\\\\\\\\
				
				
			//LanguageRegistry\\\\\\\\
				
						
		
		/**
		 * Recipes go below this notation.
		 */
		
		//Block Recipes\\\\\\\\\\\
		
		
		
		//Item Recipes\\\\\\\\\\\\
		
		
	}
	
	@PostInit
	public void load(FMLPostInitializationEvent postEvent){
		
	}

}





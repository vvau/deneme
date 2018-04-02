public void firstkit(Player p,Inventory inv)
	{
		if(plugin.getConfig().getString("sinif."+p.getUniqueId()).equalsIgnoreCase("deneme1"))
		{
			inv.setItem(0,new ItemStack(Material.BOOK,1));
			inv.setItem(1,new ItemStack(Material.WOOD_SWORD,1));
			inv.setItem(2,new ItemStack(Material.LEATHER_HELMET,1));
			inv.setItem(3,new ItemStack(Material.LEATHER_CHESTPLATE,1));
			inv.setItem(4,new ItemStack(Material.LEATHER_LEGGINGS,1));
			inv.setItem(5,new ItemStack(Material.LEATHER_BOOTS,1));
		}
		else if(plugin.getConfig().getString("sinif."+p.getUniqueId()).equalsIgnoreCase("deneme2"))
		{
			inv.setItem(0,new ItemStack(Material.BOOK,1));
			inv.setItem(1,new ItemStack(Material.WOOD_SPADE,1));
			inv.setItem(2,new ItemStack(Material.LEATHER_HELMET,1));
			inv.setItem(3,new ItemStack(Material.LEATHER_CHESTPLATE,1));
			inv.setItem(4,new ItemStack(Material.LEATHER_LEGGINGS,1));
			inv.setItem(5,new ItemStack(Material.LEATHER_BOOTS,1));
		}
		else if(plugin.getConfig().getString("sinif."+p.getUniqueId()).equalsIgnoreCase("deneme3"))
		{
			inv.setItem(0,new ItemStack(Material.BOOK,1));
			inv.setItem(1,new ItemStack(Material.BOW,1));
			inv.setItem(2,new ItemStack(Material.LEATHER_HELMET,1));
			inv.setItem(3,new ItemStack(Material.LEATHER_CHESTPLATE,1));
			inv.setItem(4,new ItemStack(Material.LEATHER_LEGGINGS,1));
			inv.setItem(5,new ItemStack(Material.LEATHER_BOOTS,1));
			inv.setItem(6,new ItemStack(Material.ARROW,64));
		}
		
		
		
		p.openInventory(inv);
		return;
	}

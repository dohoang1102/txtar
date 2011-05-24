# txtar
## Text Archiver

`txtar` is an archiver -- like `tar`. However, the archives that `txtar` outputs are human readable plain text files. Importantly, it is possible to write txtar archives directly (in a text editor) and have it output a full directory structure.

`txtar` is written in Objective-C, and as such only works on OS X. Sorry.

## Elements of a `txtar` Archive

`txtar` is very simple. Let's look at a simple directory containing fruit and vegetable sub directories. Each subdirectory contains files for different types of fruit and vegetables, each containing a short description. An archive of this would look like:

    === Fruit/Apple.txt ===
    
    The apple is the pomaceous fruit of the apple tree, species Malus domestica in the rose family (Rosaceae). It is one of the most widely cultivated tree fruits, and the most widely known of the many members of genus Malus that are used by humans.
    
    The tree originated in Western Asia, where its wild ancestor, the Alma, is still found today. There are more than 7,500 known cultivars of apples, resulting in a range of desired characteristics. Cultivars vary in their yield and the ultimate size of the tree, even when grown on the same rootstock.
    
    
    === Fruit/Banana.txt ===
    
    Banana is the common name for herbaceous plants of the genus Musa and for the fruit they produce. Bananas come in a variety of sizes and colors when ripe, including yellow, purple, and red.
    
    Almost all modern edible parthenocarpic bananas come from the two wild species Musa acuminata and Musa balbisiana. The scientific names of bananas are Musa acuminata, Musa balbisiana or hybrids Musa acuminata × balbisiana, depending on their genomic constitution. The old scientific names Musa sapientum and Musa paradisiaca are no longer used.
    
    
    === Vegetables/Carrot.txt ==
    
    The carrot (Daucus carota subsp. sativus, Etymology: Middle French carotte, from Late Latin carōta, from Greek καρότον karōton, originally from the Indo-European root ker- (horn), due to its horn-like shape) is a root vegetable, usually orange in colour, though purple, red, white, and yellow varieties exist. It has a crisp texture when fresh. The most commonly eaten part of a carrot is a taproot, although the greens are edible as well. It is a domesticated form of the wild carrot Daucus carota, native to Europe and southwestern Asia. The domestic carrot has been selectively bred for its greatly enlarged and more palatable, less woody-textured edible taproot.
    
    
    === Vegetables/Potato.txt ===
    
    The potato is a starchy, tuberous crop from the perennial Solanum tuberosum of the Solanaceae family (also known as the nightshades). The word potato may refer to the plant itself as well as the edible tuber. In the region of the Andes, there are some other closely related cultivated potato species. Potatoes were first introduced outside the Andes region four centuries ago, and have become an integral part of much of the world's cuisine. It is the world's fourth-largest food crop, following rice, wheat, and maize. Long-term storage of potatoes requires specialised care in cold warehouses.

I think you get the idea. There really is nothing else to it.
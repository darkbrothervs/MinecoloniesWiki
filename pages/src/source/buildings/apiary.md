---
type: building
building: apiary
layout: building
---
{% infobox_building %}
The Apiary is where the Beekeeper works. The Beekeeper breeds bees and harvests honeycombs or honey bottles (you can
choose which on the second page of the Apiary's GUI).

The level of the Apiary determines the max number of hives the Beekeeper can take care of:

| Apiary Level | Max Number of Hives |
|--------------|---------------------|
| 1            | 1                   |
| 2            | 2                   |
| 3            | 4                   |
| 4            | 8                   |
| 5            | 16                  |

**Note:** If the {% worker beekeeper %} is asking for hives but there are some nearby, make sure you've set the hives for them to
take care of with the hive tool. This tool is accessed from the second page of the Apiary GUI (see below).
{% endinfobox_building %}

## {% building %} GUI

{% building_gui_content_block_main order=1 %}
{% building_gui_content_block_stock order=2 %}
{% building_gui_content_block_settings order=3 %}
{% building_gui_content_block_itemlist order=4 header="flowers list" image_key="flowers" image_alt="Flower list" %}
Here you designate what flowers you want the Beekeeper to request and use during breeding.
{% endbuilding_gui_content_block_itemlist %}
{% building_gui_content_block_custom order=5 header="hive tool" image_key="hivetool" image_alt="Hive tool" %}
Click this button to get the hive tool, which is how you select which hives the {% worker beekeeper %} will take care of. To select a hive, right-click on it with the hive tool. Right-click on a hive again to remove it.
{% endbuilding_gui_content_block_custom %}
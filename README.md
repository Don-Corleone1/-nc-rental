Download the script and put it in the [resource] folder.
Download nh-context and put it in the [resource] or [standalone] folder. (it doesn't really matter) Add the following code to your server.cfg/resouces.cfg



Dependencies
nh-context
qb-menu

["rentalpapers"]				 = {["name"] = "rentalpapers", 					["label"] = "Rental Papers", 			["weight"] = 50, 		["type"] = "item", 		["image"] = "rentalpapers.png", 		["unique"] = true, 		["useable"] = false, 	["shouldClose"] = false, 	["combinable"] = nil, 	["description"] = "This car was taken out through car rental."},


Inventory image


![image](https://user-images.githubusercontent.com/123836372/215288337-93df57f8-6e97-4101-abc9-defc25693334.png)


Add the rentalpapers.png to your - inventory -> html -> images



          } else if (itemData.name == "rentalpapers") {
            $(".item-info-title").html('<p>' + itemData.label + '</p>')
            $(".item-info-description").html('<p><strong>Plate: </strong><span>'+ itemData.info.label + '</span></p>');

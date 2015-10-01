# Rainfall_Model
This is a model of Rainfall and water runoff. It simulates the runoff of the rain. This model is inspired by the Grand Canyon Model.

The map being used is the crater lake national park in Oregon. 

Rain drops are created ramdonly on the map based on the rain rate parameter. Rain drops will run to the neighboring patch with the lowest elevation. Besides, if there are already water in a patch, the height of water will also be added to its elevation, when raindrops are selecting the patch to run to. If a raindrop can not find a neighboring patch with lower elevation, it will stay where it is and become water. When raindrops run to the edge of the map, they are removed from this model.




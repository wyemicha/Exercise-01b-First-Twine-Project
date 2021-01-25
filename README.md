# Exercise-01b-First-Twine-Project
Exercise for MSCH-C220, 25 January 2021

This exercise is an opportunity for you to create your first project in Twine, the open-source tool for creating non-linear interactive stories (interactive fiction). You should have installed [Twine 2.3.11](https://twinery.org/) as part of your last exercise; if not, please do so now.

Fork this repository. When that process has completed, make sure that the top of the repository reads [your username]/Exercise-01b-First-Twine-Project. *Edit the LICENSE and replace BL-MSCH-C220-S21 with your full name.* Commit your changes.

Press the green "Code" button and select "Open in GitHub Desktop". Allow the browser to open (or install) GitHub Desktop. Once GitHub Desktop has loaded, you should see a window labeled "Clone a Repository" asking you for a Local Path on your computer where the project should be copied. Choose a location where you will keep the repositories for this class (a C220 folder off your Desktop would be fine). Make sure the Local Path ends with "Exercise-01b-First-Twine-Project" and then press the "Clone" button. GitHub Desktop will now download a copy of the repository to the location you indicated.

Open Twine, and press the "+ Story" button in the right side bar. When you are asked what your story should be named, enter "Adventure". Press the "+Add" button to get started.

You should now see a window with a blue grid background. There should be a node in the middle of the window labeled "Untitled Passage". Double click on the node to open it.

On the top line of the resulting window, change "Untitled Passage" to "Road". Then replace the description ("Double-click this passage to edit it.") with the following:
```
You are standing at the end of a road before a small brick building. Around you is a forest.  A small stream flows out of the building and down a gully.

[[Go North->Forest]]
[[Go East->Building]]
[[Go South->Valley]]
[[Go West->Hill]]
```

Close that window, and you should now see that the node is now labeled "Road" and that there are four arrows pointing to newly created nodes: Forest, Building, Valley, and Hill.

Select Forest and replace the description with the following:
```
You are in open forest, with a deep valley to one side.

[[Go North->Forest]]
[[Go East->Building]]
[[Go South->Road]]
[[Go West->Hill]]
```

Close the window; you should see new arrows that connect the node to itself and the other nodes.

Select Building and replace the description with the following:
```
You are inside a building, a well house for a large spring.

[[Go North->Forest]]
[[Go East->Building]]
[[Go South->Valley]]
[[Go West->Road]]
```

Close the window. Select Valley and replace the description with the following:
```
You are in a valley in the forest beside a stream tumbling along a rocky bed.

[[Go North->Road]]
[[Go East->Building]]
[[Go South->Valley]]
[[Go West->Hill]]
```

Close the window. Select Hill and replace the description with the following:
```
You have walked up a hill, still in the forest.  The road slopes back
down the other side of the hill.  There is a building in the distance.

[[Go North->Forest]]
[[Go East->Road]]
[[Go South->Valley]]
[[Go West->Hill]]
```

Close the window. Down in the bottom right corner of the workspace is a button labeled "Play". Press that now.

The game should load in your browser. You should be able to press the links to take you from one location to another.

When you are done, return to Twine. On the bottom bar press the "Adventure" label. In the resulting menu, select "Publish to File".

Navigate to the location of your repository in your file system. Save the file as Adventure.html in the repository (Exercise-01b-First-Twine-Project) folder.

Quit Twine. In GitHub desktop, you should now see Adventure.html listed in the left panel. In the bottom of that panel, type a Summary message (something like "Adds a simple version of the Adventure Interactive Fiction game") and press the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push origin". Press that now.

If you return to and refresh your GitHub repository page, you should now see Adventure.html listed among the files.

Now edit the README.md file. When you have finished editing, commit your changes, and then turn in the URL of the main repository page (https://github.com/[username]/Exercise-01b-First-Twine-Project) on Canvas.

The final state of the file should be as follows (replacing my information with yours):
```
# Exercise-01b-First-Twine-Project
Exercise for MSCH-C220, 25 January 2021

An Interactive Fiction game loosly based on the original, great Interactive Fiction game, Adventure. Load Adventure.html in a browser to play it.

## Implementation
Built using Twine 2.3.11

## References
[Adventure, 1976 by Will Crowther and Don Woods](https://quuxplusone.github.io/Advent/play.html)

## Future Development
None

## Created by 
Jason Francis

```

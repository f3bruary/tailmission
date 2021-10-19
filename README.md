# tailmission
A TailwindCSS refresh for the Transmission Bittorrent web interface

This repository contains a custom.css file and a directory with icon file. Place both in `/usr/share/transmission/web/style/transmission/` or wherever you have installed Transmission Bittorrent.

Then edit your (existing) index.html file (`/usr/share/transmission/web`) and remove the 2 current stylesheets on line 19 and 20 and add the custom one:
`<link href="./style/transmission/custom.css" type="text/css" rel="stylesheet" />`

Clear your cache and refresh the instance.

Notes:

- Mobile responsiveness hasn't been tested thouroughly, so there could be bugs.
- It's still a work in progress. Feel free to submit an issue if you find anything wrong.

![Screen Shot 2021-10-19 at 22 18 02](https://user-images.githubusercontent.com/5641933/137986162-e271224e-2c4e-499a-8845-12fcee4d4a15.png)
![Screen Shot 2021-10-19 at 22 18 07](https://user-images.githubusercontent.com/5641933/137986182-bbd69401-c967-4089-af74-b6b3e018b2bc.png)
![Screen Shot 2021-10-19 at 22 18 20](https://user-images.githubusercontent.com/5641933/137986188-2d395409-c679-419b-abdf-9be5439f6d6d.png)
![Screen Shot 2021-10-19 at 22 18 44](https://user-images.githubusercontent.com/5641933/137986195-7cecd181-3981-470e-a124-a5a250dae6d6.png)

# NeonNode
 Archcraft i3 Custom Theme Based in Archcraft Nordic for 13wm

Work in progress
![Alt text](screenshots/Screenshot_2023-10-08-13-38-51_2560x1440.png)

![Alt text](screenshots/Screenshot_2023-10-08-13-36-57_2560x1440.png)



This lines wont change back when you change theme, either you change them manually or add the lines to all other themes
-e "s/active-opacity = .*/active-opacity = $picom_active_opacity;/g" \
-e "s/inactive-opacity = .*/inactive-opacity = $picom_inactive_opacity;/g" \
-e "s/\"window_type = 'dock'\",/\"window_type = '#dock'\",/g" \
-e "s/\"100:class_g    = 'Alacritty'\",/\"100:class_g    = '#Alacritty'\",/g"
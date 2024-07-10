# Avatar Gallery Plugin for NodeBB

[https://community.nodebb.org/](https://community.nodebb.org/post/100296)

A NodeBB plugin to display a gallery of avatars that users can select from and which admins can manage.

## Installation

Really simple, just install the plugin with `npm install nodebb-plugin-avatar-gallery` or via your forum's admin control panel. Then upload some avatars using the admin control panel. You can specify the access level for each avatar in the admin panel, so you can have avatars that are reserved for administrator or moderator use only.

## Configuration

Currently avatars are uploaded to /uploads/avatars/ and are given a unique id. In the future I might add configurable settings for this.

## Screenshots

### User facing change picture

![Avatar Gallery](https://github.com/SinisterSpatula/nodebb-plugin-avatargallery/blob/main/gallery.png)

### Admin Control Panel

![Avatar Gallery Admin](https://github.com/SinisterSpatula/nodebb-plugin-avatargallery/blob/main/gallery2.png)

### Notes

Users will only see the avatars for which they have the access level. Users can change their own avatars only. Admins and can change other user avatars. When enabling the plugin, avatar image uploads will be disabled, users must select an avatar from the gallery only.

Let me know what you think!

### Updates

- v1.0.0 - initial release
- v1.0.1 - fixed issue where the modal would not open on some account pages.

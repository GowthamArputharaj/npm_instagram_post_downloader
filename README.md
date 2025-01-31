![Image of easy-instagram-post-downloder](https://raw.githubusercontent.com/GowthamArputharaj/images/main/easy-instagram-post-downloder.png)

> Get links of the publically shared medias on Instagram.

# Install
$ npm install --global easy-instagram-post-downloader


# Instagram Post Downloader Usage
```javascript
const insta = require('easy-instagram-post-downloader');

// https://www.instagram.com/p/{postId}/
var postId = 'CM9i3rEKRBX';

// create downloads directory and get relative path
var dirName = './downloads';

insta(postId, dirName, (error, response) => { 
    if(error) console.log(`Error is: ${err}`); 
    if(response) console.log(response);
});
```

# Sample Output Response
```
URL is https://www.instagram.com/p/CM9i3rEKRBX/?__a=1

```json
{
  graphql: {
    shortcode_media: {
      __typename: 'GraphImage',
      id: '2539339124300124247',
      shortcode: 'CM9i3rEKRBX',
      dimensions: [Object],
      gating_info: null,
      fact_check_overall_rating: null,
      fact_check_information: null,
      sensitivity_friction_info: null,
      sharing_friction_info: [Object],
      media_overlay_info: null,
      media_preview: 'ACoqRGJPHerA4PvUC/MRj1qwo3kkdsg1nex0NWIyc9ah34OB2z9fzrQEYwe9U/KJyf071HMC1ImYHk8459PSmh+OtVyhJxnAOBSmMA43dPb/AOtV3sVy+RbDbjuPXpgcVb84IoYcYzkd/r781XEixj2PAPbgZ/l+dRSvuTOAV4OD7+lKWot2accm7g8Y70hkXdg46fnWalyx2qy4Lcf0/KoJ5ucdcYyenf1rBU22K1tyxOF3k9/pkHPoex9Afzqlu/3qFm2tu3YJJUADOD0B+n646UxpY8nKvnPOPWtlHuUp22LCbmYspwOeCMDrjA7ZI/TjvSNHJMwwhHY85IUegJ6+nWproneB23gfh6Um4/aOp6H+lPsZJtfMa0cp/eomfL4CnHHHBx3Pcmq7SEjccbmxn2x2Hbrk/pV5WPmPyeq/yrHJwgx/e/rTXYrf7i0JXChBhWGckjn2z7moDet6mnzDaqkcEgk49eaoVZmf/9k=',
      display_url: 'https://instagram.fmaa12-1.fna.fbcdn.net/v/t51.2885-15/fr/e15/s1080x1080/165076931_2939140333034008_2583165412809239535_n.jpg?tp=1&_nc_ht=instagram.fmaa12-1.fna.fbcdn.net&_nc_cat=104&_nc_ohc=6VDscrPLKS4AX9Ghu9s&ccb=7-4&oh=5198980a76bf18cc66cf54f07c545cab&oe=608822D0&_nc_sid=83d603',
      display_resources: [Array],
      accessibility_caption: 'Holi festival celebrations burst into colour in Nandagon, India. \n' +
        '\n' +
        'The Hindu festival of Holi, also known as the Festival of Colours, heralds the beginning of spring. It began in India as far back as the 4th century, but is now celebrated all over the world and is recognizable by its vast array of celebratory coloured powders.',
      is_video: false,
      tracking_token: 'eyJ2ZXJzaW9uIjo1LCJwYXlsb2FkIjp7ImlzX2FuYWx5dGljc190cmFja2VkIjp0cnVlLCJ1dWlkIjoiYmU5NTEwNGU5MzEzNGIyOTk2YTY2YTA3YzY2MGY3MWUyNTM5MzM5MTI0MzAwMTI0MjQ3In0sInNpZ25hdHVyZSI6IiJ9',
      edge_media_to_tagged_user: [Object],
      edge_media_to_caption: [Object],
      caption_is_edited: false,
      has_ranked_comments: false,
      edge_media_to_parent_comment: [Object],
      edge_media_to_hoisted_comment: [Object],
      edge_media_preview_comment: [Object],
      comments_disabled: false,
      commenting_disabled_for_viewer: false,
      taken_at_timestamp: 1616932834,
      edge_media_preview_like: [Object],
      edge_media_to_sponsor_user: [Object],
      location: null,
      viewer_has_liked: false,
      viewer_has_saved: false,
      viewer_has_saved_to_collection: false,
      viewer_in_photo_of_you: false,
      viewer_can_reshare: true,
      owner: [Object],
      is_ad: false,
      edge_web_media_to_related_media: [Object],
      edge_related_profiles: [Object]
    }
  }
}
```

downloads\14049126411806867.jpeg

# License
ISC © [Gowtham](https://github.com/GowthamArputharaj)

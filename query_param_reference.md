## Useful Engagement Query Parameters for Testing and Demo'ing

Usage: Append query parameter(s) to engagement serve.truex.com URLs.  
Example: **`&debug=true`**

| Query Parameter  | Possible Values | Description |
| ------------- | ------------- | ------------- |
| debug  | `true`  | Enables debug output.  |
| test_player  | `true`  | Loads container in a test player w/ play/pause/mute/fullscreen functionality  |
| test_placement_id  | `PLACEMENT ID`  | Sets the placement ID.  Useful for testing placement ID tag restriction.  |
| test_campaign_id  | `CAMPAIGN ID`  | Sets the campaign ID.  Useful for testing campaign ID tag restriction.  |
| test_start_date  | `MM/DD/YYYY`  | Sets a particular date for your debug link.  Useful for testing start date tag restriction.  |
| test_end_date  | `MM/DD/YYYY`  | Sets a particular date for your debug link.  Useful for testing end date tag restriction.  |
| test_variant  | `A or B`  | Sets a variant for your debug link.  Useful for variant tag restriction.  |
| cap_type  | `value_added_units`  | Sets the campaign unit type.  Useful for testing Added Value tag restriction.  |
| true_attention_seconds  | `SECONDS`  | Sets the amount of True Attention seconds.  |
| fire_tracking  | `true`  | Enables firing of 3rd-party tracking pixels.  |
| disable_surveys  | `true`  | Disables Qualtrics and Vizu surveys from running.  |
| has_autoplay_intro_video  | `true`  | Indicates creative has an autoplay intro video.  Used by container to know when to detect autoplay is disabled by the browser and show a 'click to play' step before engagement begins.  |
| has_autoplay_intro_video  | `true`  | Indicates creative has an autoplay intro video.  Used by container to know when to detect autoplay is disabled by the browser and show a 'click to play' step before engagement begins.  |

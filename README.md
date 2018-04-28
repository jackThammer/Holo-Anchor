# Holo-Anchor

This is created to set-up anchors for you application.
Makes it easy to refer back to the data that is saved.

## Methods provided are

### anchor(anchor)
This is used to setup  anchors
> Input : anchor{anchorType: "", anchorText: ""}
Example : anchor(anchor{anchorType: "hashtag", anchorText: "hammer"});

### exists(anchor)
This is used to check if an anchor exist it will return a true or false is response
> Input : anchor{anchorType: "", anchorText: ""}
Example : exists(anchor{anchorType: "hashtag", anchorText: "hammer"});

### getAnchor(anchorType)
This will get the link of the anchorType
> Input : anchorType  (string)
> Example : getAnchor(hashtag);

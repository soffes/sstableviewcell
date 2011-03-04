## SSTableViewCell

Simple, fast table view cell based on [ABTableViewCell](http://blog.atebits.com/2008/12/fast-scrolling-in-tweetie-with-uitableview/).

Just override `drawContentView:` and write your `drawRect:` code for the cell's inner view.

### Notes

Unlike ABTableViewCell, it adds the custom view to UITableViewCell's `contentView` so it allows for resizing and `backgroundView` to `selectedBackgroundView` animations better.

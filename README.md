/**
 * Displays an image, such as an icon.
 */
public class ImageView extends View {
 
    // Resource ID for the source image that should be displayed in the ImageView.
    private int mImageId;
 
    // Context of the app
    private Context mContext;

    /**
     * Constructs a new ImageView.
     */
    public ImageView(Context context) {
        mImageId = 0;
        mContext = context;
    }
 
    /**
     * Sets the source image in the ImageView.
     *
     * @param imageId is the resource ID of the image to be displayed.
     */
    public void setImage(int imageId) {
        mImageId = imageId;
    }
}

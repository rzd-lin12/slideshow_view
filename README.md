# slideshow_view
可轮询viewpager
##该类中的一些方法
### 
   /**
     * 加载图片资源
     *
     * @param imageUrls 图片地址
     */
    public void setImageUrls(String[] imageUrls)
    
   /**
     * 设置没有选中时候的小圆点
     *
     * @param imageRes 图片的id
     */
    public void setBlurDotImageRes(int imageRes)
    
    /**
     * 设置选中时候的小圆点
     *
     * @param imageRes 图片的id
     */
    public void setFocusDotImageRes(int imageRes)
    
    /**
     * 设置手动滑动
     * 默认为自动轮播
     *
     * @param isManual
     */
    public void setManualPlay(boolean isManual) 
    
    /**
     * 判定轮播是否开启
     *
     * @return
     */
    public boolean isPlay() 

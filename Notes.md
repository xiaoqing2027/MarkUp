#Notes
* week4
 * Android Drop and Drag: http://www.vogella.com/tutorials/AndroidDragAndDrop/article.html
   * Allowing a view to be dragged: onTouchListener/LongClickListener, startDrag(clipdata,DragShadowBuilder,view,0)
    * Defining drop target: OnDragListener(be assigned by setOnDragListener),FiveState(DragEvent.ACTION_DRAG_STARTED,DRAG_ENTERED,DROP,DRAG_ENDED)
 * R.java missing problem: you can find R.java in the path: app/build/generated/source/r/debug/(packgename)/R.java
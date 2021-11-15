
### Create dynamic lists with RecyclerView:
* RecyclerView makes it easy to efficiently display large sets of data. You supply the data and define how each item looks.
* Key classes:
    - RecyclerView:  the ViewGroup that contains the views corresponding to your data.
    -  RecyclerView.ViewHolder :  Each individual element in the list is defined by a view holder object, and after the view holder is created, the RecyclerView binds it to its data.
    -  RecyclerView.Adapter : RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter.
    -  LayoutManager : arranges the individual elements in your list.

`>>`  Plan your layout:

* LinearLayoutManager arranges the items in a one-dimensional list
* GridLayoutManager arranges all items in a two-dimensional grid
* StaggeredGridLayoutManager is similar to GridLayoutManager, but it does not require that items in a row have the same height or items in the same column have the same width. The result is that the items in a row or column can end up offset from each other.

* Adapter and ViewHolder classes work together to define how your data is displayed.
  
 
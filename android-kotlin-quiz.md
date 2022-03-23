## Android

#### Q1. To add features, components, and permissions to your Android app, which file needs to be edited?

- [x] AndroidManifest.xml
- [ ] Components.xml
- [ ] AppManifest.xml
- [ ] ComponentManifest.xml

#### Q2. Why might push notifications stop working?

- [x] all of these answers
- [ ] The device token is not being sent to push provider correctly.
- [ ] Google Play Services is not installed on the deivce/emulator.
- [ ] Battery optimization is turned on on the device.

#### Q5. What is the correct set of component classes needed to implement a RecyclerView of items that displays a list of widgets vertically?

- [ ]

```
      RecycleView
      RecyclerView.Adapter<T extends BaseAdapter>
      RecyclerView.ViewHolder<T extends BaseViewHolder>
      LinearLayoutManager
```

- [ ]

```
      RecycleView
      RecyclerView.Adapter
      RecyclerView.ViewHolder<T extends BaseViewHolder>
      LinearLayoutManager
```

- [ ]

```
      RecycleView
      RecyclerView.Adapter
      RecyclerView.ViewHolder
      LinearLayoutManager
```

- [x]

```
      RecycleView
      RecyclerView.Adapter<VH extends ViewHolder>
      RecyclerView.ViewHolder
      LinearLayoutManager
```

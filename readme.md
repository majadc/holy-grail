# Holy Grail Layout

The CSS Page Layout based on flexbox layout.

[majadc.com/holy-grail/](https://majadc.com/holy-grail/)

## Structure:

- Header
- Footer
- There Columns:
  - Sidebar on the left
  - Main Column
  - Sidebar on the right

The three columns are built based on CSS flexbox.

```
.holy-grail-layout {
  display: flex;
  flex-direction: column;
}
.holy-grail__main {
  flex: 1; /* flex: 1 1 0% /*
}
.holy-grail__sidebar {
  flex: 1; /* flex: 1 1 0% /*
}
```

```
@media only screen and (min-width: 48em) {
  .holy-grail-layout {
    flex-direction: row;
  }
  .holy-grail__sidebar {
    flex: 0 0 20%;
  }
}
```

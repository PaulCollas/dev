# Comment gérer la homepage

## Sommaire 

- Architecture
- Header
- Carrés 


Enlever block doc :

```json
v-application--wrap {
    min-height: 0vh
}
.v-main {
    display: none;
    min-height: 0vh
}
.v-footer {
    display: none;
}
.v-navigation-drawer {
    display: none;
}
```


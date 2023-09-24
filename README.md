# JavaFX CSS Support for VS Code

Get JavaFX CSS support in Visual Studio Code.  
Only JavaFX 17 is currently supported!

The CSS properties were obtained using [@startball5](https://github.com/starball5)'s script, that he published [here](https://stackoverflow.com/a/75946319).
All credit goes to him! I only made it an extension for ease of use.

---

### Disable vendorPrefix warning

To disable the vendorPrefix warning, add the following to your Workspace's settings.json:

```json
"css.lint.vendorPrefix": "ignore"
```

---

### Add errors or warning to unknown Vendor Specific Properties

To add errors or warning to unknown properties, add the following to your Workspace's settings.json:

```json
"css.lint.unknownVendorSpecificProperties": "error"
```
or  
```json
"css.lint.unknownVendorSpecificProperties": "warning"
```

---

**Enjoy!**

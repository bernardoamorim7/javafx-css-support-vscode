# JavaFX CSS Support for VS Code

Get JavaFX CSS support in Visual Studio Code.  
Only JavaFX 17 is currently supported!

---

### Disable vendorPrefix warning

To disable the vendorPrefix warning, add the following to your Workspace's settings.json:

```json
"css.lint.vendorPrefix": "ignore"
```

---

### Add errors or warning to unkwnown properties

To add errors or warning to unkwnown properties, add the following to your Workspace's settings.json:

```json
"css.lint.unknownVendorSpecificProperties": "error"

or

"css.lint.unknownVendorSpecificProperties": "warning"
```

---

**Enjoy!**

# Blackwall (Botguard) Website Protection Module for WHMCS

This WHMCS module integrates Blackwall (Botguard) website protection into your hosting products with gatekeeper support and optional DNS management automation.

## 📦 Installation

1. **Upload the module files**  
   Copy the contents of this repository into the following directory in your WHMCS installation:

/modules/servers/blackwall

markdown
Copy
Edit

2. **Create a new product**
- Navigate to:  
  `System Settings > Products/Services > Create a Product`
- Choose your desired product group and type.
- Under **Details**, ensure **Require Domain** is enabled.

3. **Configure the module settings**
- Go to the **Module Settings** tab.
- Select `Blackwall (Botguard) Website protection` as the **Module Name**.
- The following settings are already **hardcoded** into the module (can be changed in the source files if needed):
  - **API Key**
  - **Primary and Secondary Botguard Servers**
- Check the box to **Enable Gatekeeper Integration**.

4. **Save your changes**  
Click **Save Changes** to complete the setup.

---



## 📄 License

MIT License. Feel free to use, modify, and distribute.

---

## 🤝 Contributions

Pull requests and improvements are welcome. Please ensure code is properly commented and tested before submission.

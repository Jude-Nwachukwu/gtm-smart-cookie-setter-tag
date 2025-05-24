# Cookie Setter (Smart) — GTM Custom Tag Template

**Cookie Setter (Smart)** is a Google Tag Manager (GTM) **custom tag template** designed to give you fine-grained control over how cookies are set in the browser.

Whether you're tracking session activity, setting feature flags, or preserving visitor preferences, this template ensures you do it efficiently and intelligently—without overwriting existing values unnecessarily.

> Developed with 😍 by **Jude Nwachuwku Onyejekwe** for [DumbData](https://dumbdata.co/)


---

## 🚀 Features

- Set cookies with custom names and values
- Configure cookie duration in seconds, minutes, hours, or days
- Optionally prevent setting cookies if the value is `undefined`, `null`, or empty
- Control whether the cookie lifespan refreshes on every tag execution
- Customize cookie domain and path
- Automatically avoids redundant overwriting of cookies when values haven't changed

---

## 📦 How to Import the Tag Template

1. Open [Google Tag Manager](https://tagmanager.google.com/).
2. Navigate to **Templates** > **Tag Templates** > **New**.
3. Click the **three-dot menu** > **Import**.
4. Upload the `.tpl` file for this template.
5. Save and name it something like: `Cookie Setter (Smart)`.

---

## 🛠️ How to Configure

After importing, add a new tag and select **Cookie Setter (Smart)** as the tag type. Configure the following fields:

### Required Fields
- **Cookie Name**:  
  The name of the cookie to be created. Example: `gtm_user_session`.

- **Cookie Value**:  
  The value to be assigned to the cookie. Can be a GTM variable (e.g. `{{User ID}}`).

- **Cookie Duration**:  
  Choose the time unit for the cookie lifespan:  
  `Seconds`, `Minutes`, `Hours`, or `Days`.

- **Cookie Lifespan**:  
  The number of units (based on the selected duration) the cookie should remain valid.

---

### Optional Behaviors
- **Update the cookie's lifespan on each tag execution**  
  When enabled, the cookie’s expiration time will be refreshed each time the tag fires.

- **Do not set the cookie if the value is undefined, null, or empty**  
  Prevents setting a cookie if its value is invalid.

---

### Advanced Configuration
(Expandable in GTM)

- **Set a custom domain**  
  Enable and enter a specific domain for the cookie (e.g., `example.com`).

- **Set a custom cookie path**  
  Enable and enter a path (e.g., `/` or `/products`).

---

## 📄 License

Licensed under the [Apache 2.0 License](LICENSE).

---

## 👨‍💻 Developed By

This tag template was developed by **Jude Nwachukwu Onyejekwe** for [DumbData](https://dumbdata.co/).

For inquiries, feature requests, or support, feel free to [contact DumbData](https://dumbdata.co/contact-us/).

---

## 💡 More Templates & Support

Explore more GTM custom templates from DumbData:  
👉 [https://dumbdata.co/gtm-custom-templates/](https://dumbdata.co/gtm-custom-templates/)

---

## 🐛 Found an Issue?

You’re welcome to [raise an issue](../../issues) in this repository if you encounter bugs or need enhancements.

---


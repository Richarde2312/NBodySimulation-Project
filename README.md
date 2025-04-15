# 📚 How to Install Necessary Libraries


---

## 🛠 Installation Instructions

Click a section below to jump directly to the relevant setup instructions:

- [BlueJ](#-bluej)
- [NetBeans](#-netbeans)
- [Visual Studio Code](#-visual-studio-code)
- [IntelliJ IDEA](#-intellij-idea)
- [Maven](#-maven)

---

## 📘 BlueJ

1. **Start BlueJ**
2. Go to `Tools` → `Preferences`
3. **Add Libraries**:
   - Open the **Libraries** tab.
   - Click **Add** and navigate to the `lib/` folder in the project.
   - Inside each sub-library folder, open the `lib/` subdirectory and select **all `.jar` files**.
4. **Reset JVM**: Go to `Tools` → `Reset Java Virtual Machine` or restart BlueJ.

> ⚠️ **Note:** On **Mac** or **Linux**, download JavaFX from [Gluon](https://gluonhq.com/products/javafx/)

---

## 🌟 NetBeans

1. **Start NetBeans**
2. Open your existing project or create a new one.
3. **Add Libraries**:
   - Right-click your project in the **Projects** tab → `Properties`
   - Navigate to `Libraries` → `Compile`
   - Click **Add JAR/Folder** → select all `.jar` files from the `lib/**/lib` directories
4. Click **OK** to apply.

> ⚠️ On Mac/Linux, use [Gluon](https://gluonhq.com/products/javafx/) to install JavaFX.

---

## 🖥 Visual Studio Code

1. **Install Java Extension Pack** from the Extensions Marketplace (`Ctrl+Shift+X`)
2. **Open or Create Your Java Project**
3. Create a `lib/` directory if it doesn't exist, and add `.jar` files there
4. **Update `.classpath`** in the root of your project:
   ```xml
   <classpathentry kind="lib" path="lib/library-name.jar"/>

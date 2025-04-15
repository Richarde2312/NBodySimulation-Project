# 📚 How to Install Necessary Libraries

This guide provides step-by-step instructions for including external libraries in Java projects using:

- [BlueJ](#-bluej)
- [NetBeans](#-netbeans)
- [Visual Studio Code](#-visual-studio-code)
- [IntelliJ IDEA](#-intellij-idea)
- [Maven](#-maven)

---

## 📘 BlueJ

1. **Open BlueJ**
   - Start BlueJ.

2. **Access Preferences**
   - Navigate to `Tools` → `Preferences`.

3. **Add Libraries**
   - Go to the **Libraries** tab.
   - Click **Add** and navigate to the `lib` directory where your JAR files are located.
   - Each library in the provided `lib` directory has its own internal `lib` directory.
   - Select **all JAR files** inside each internal `lib` directory.

4. **Reset Java Virtual Machine**
   - Either close and reopen BlueJ, or go to `Tools` → `Reset Java Virtual Machine`.

> 💡 **Note:** On **Mac** or **Linux**, you may need to download the appropriate version of JavaFX from [Gluon](https://gluonhq.com/products/javafx/).

---

## 🌟 NetBeans

1. **Open NetBeans**
   - Start NetBeans.

2. **Create or Open a Java Project**
   - Open your existing Java project or create a new one.

3. **Add Libraries**
   - Right-click the project in the **Projects** tab.
   - Select `Properties`.
   - Go to `Libraries` → `Compile`.
   - Click **Add JAR/Folder** and navigate to the `lib` directory.
   - Select **all JAR files** inside each internal `lib` directory.

4. **Apply and Close**
   - Click **OK** to close the Project Properties dialog.

> 💡 **Note:** On **Mac** or **Linux**, download JavaFX from [Gluon](https://gluonhq.com/products/javafx/).

---

## 🖥 Visual Studio Code

1. **Open Visual Studio Code**
   - Start VS Code.

2. **Install Extensions**
   - Open the Extensions view (`Ctrl+Shift+X`).
   - Search for and install the **Java Extension Pack**.

3. **Create or Open a Java Project**
   - Open your Java project folder or create a new one.

4. **Configure Classpath**
   - Create a folder named `lib` in your project directory (if it doesn't already exist).
   - Place all necessary JAR files into the `lib` folder.

5. **Update `.classpath` File**
   - Open the `.classpath` file in your project’s root directory.
   - Add entries for each JAR file like the following:
     ```xml
     <classpathentry kind="lib" path="lib/library-name.jar"/>
     ```

6. **Refresh Project**
   - Right-click your project in the Explorer view and select **Refresh**.

---

## 💡 IntelliJ IDEA

1. **Open IntelliJ IDEA**
   - Start IntelliJ.

2. **Open Project**
   - Open your existing Java project or create a new one.

3. **Access Project Structure**
   - Go to `File` → `Project Structure`.

4. **Add Libraries**
   - In the Project Structure dialog:
     - Navigate to `Libraries`.
     - Click the **+** button → Select **Java**.
     - Navigate to the `lib` directory and add all required JAR files.

5. **Apply and Close**
   - Click **Apply** and then **OK**.

> 💡 **Note:** On **Mac** or **Linux**, download JavaFX from [Gluon](https://gluonhq.com/products/javafx/).

---

## 📦 Maven

1. **Open Project in NetBeans or IntelliJ IDEA**
   - Open your Maven project in **NetBeans** or **IntelliJ IDEA**.

2. **Verify `pom.xml`**
   - Ensure the provided `pom.xml` file is in the root of your project.
   - It should include dependencies for:
     - Apache Commons Math
     - Apache Commons Numbers
     - JavaFX

3. **Build the Project**

   - **In NetBeans**
     - Right-click the project in the **Projects** tab.
     - Select **Build**.

   - **In IntelliJ IDEA**
     - Open the **Maven** tool window (usually on the right side).
     - Click **Reimport All Maven Projects**, or right-click your project and select `Maven` → `Reimport`.

---

## 📥 JavaFX Download

> 💡 If you're on **Mac** or **Linux**, you may need to manually download JavaFX:
> - 🔗 [Download JavaFX from Gluon](https://gluonhq.com/products/javafx/)

---




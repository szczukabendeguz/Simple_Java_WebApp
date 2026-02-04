# Simple Java WebApp

A simple Bookstore application built with Java Servlets and JSP.

## Tech stack

[![Tech stack](https://skillicons.dev/icons?i=java,maven,html,css)](https://skillicons.dev)

## Project goal

This project is a lightweight web application designed to demonstrate the fundamentals of Java web development. It provides a simple Bookstore interface where users can log in, browse available books, and manage a virtual shopping cart, all using session-based state management.

## Getting started

### Prerequisites
- **Java 11** or higher
- **Maven** (optional, uses `mvnw` wrapper)
- A Servlet container like **Apache Tomcat 10+** (Jakarta EE 9+ compatible)

### Execution
1. Clone the repository.
2. Build the project using the Maven wrapper:
   ```bash
   ./mvnw clean package
   ```
3. The generated `.war` file can be found in the `target/` directory:
   `target/demo1-1.0-SNAPSHOT.war`
4. Deploy this WAR file to your preferred Servlet container (e.g., Tomcat, GlassFish, or WildFly).

## Architecture / key components

- **Controllers**: Jakarta Servlets (`LoginServlet`, `BuyServlet`) handle incoming requests and manage session data.
- **Models**: The `Book` class represents the data entity with attributes like ISBN, title, and author.
- **Repository**: A singleton `repo` class provides in-memory storage for the book collection.
- **Frontend**: JSP (JavaServer Pages) coupled with Vanilla CSS for the user interface and presentation logic.

---

# Simple Java WebApp

Egy egyszerű Könyvesbolt alkalmazás Java Servlets és JSP használatával.

## Tech stack

[![Tech stack](https://skillicons.dev/icons?i=java,maven,html,css)](https://skillicons.dev)

## Project goal

Ez a projekt egy könnyűsúlyú webapplication, amely a Java webfejlesztés alapjait hivatott bemutatni. Egy egyszerű Bookstore felületet biztosít, ahol a felhasználók elvégezhetik a login folyamatot, böngészhetik az elérhető könyveket, és kezelhetik a virtuális kosarukat, mindezt session-alapú state management segítségével.

## Getting started

### Prerequisites
- **Java 11** vagy újabb
- **Maven** (opcionális, a `mvnw` wrapper-t használja)
- Egy Servlet container, például **Apache Tomcat 10+** (Jakarta EE 9+ kompatibilis)

### Execution
1. Klónozd a repository-t.
2. Build-eld a projektet a Maven wrapper használatával:
   ```bash
   ./mvnw clean package
   ```
3. A generált `.war` file a `target/` directory-ban található:
   `target/demo1-1.0-SNAPSHOT.war`
4. Deploy-old ezt a WAR file-t a választott Servlet container-ben (pl. Tomcat, GlassFish, vagy WildFly).

## Architecture / key components

- **Controllers**: Jakarta Servlets (`LoginServlet`, `BuyServlet`) kezelik az érkező request-eket és a session data-t.
- **Models**: A `Book` class reprezentálja az entity-t olyan attribútumokkal, mint az ISBN, title és author.
- **Repository**: Egy singleton `repo` class biztosítja az in-memory storage-ot a könyvgyűjtemény számára.
- **Frontend**: JSP (JavaServer Pages) és Vanilla CSS a user interface és a megjelenítési logic számára.

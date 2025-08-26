
# Smart Contact Management System 2.0

A modern web-based contact management application built with Java (Spring Boot), Maven, and Tailwind CSS.

## Features
- User registration and authentication (including OAuth)
- Add, update, delete, and search contacts
- User dashboard and profile management
- Responsive UI with Tailwind CSS
- Admin and user roles
- Error and success messaging

## Tech Stack
- **Backend:** Java, Spring Boot
- **Frontend:** HTML, Tailwind CSS, JavaScript
- **Build Tool:** Maven
- **Database:** (Configure in `application.properties`)
- **Containerization:** Docker (optional)

## Getting Started

### Prerequisites
- Java 17 or higher
- Maven
- Node.js & npm (for Tailwind CSS)
- Docker (optional)

### Setup
1. **Clone the repository:**
	```sh
	git clone https://github.com/Prabhu0414/Smart_contact_managment.git
	cd scm2.0-main
	```
2. **Install dependencies:**
	- For Java: `mvn clean install`
	- For Tailwind CSS: `npm install`
3. **Build Tailwind CSS:**
	```sh
	npx tailwindcss -i ./src/main/resources/static/css/input.css -o ./src/main/resources/static/css/output.css --watch
	```
4. **Configure the database:**
	- Edit `src/main/resources/application.properties` with your DB credentials.
5. **Run the application:**
	```sh
	./mvnw spring-boot:run
	```
	Or with Docker:
	```sh
	docker-compose up --build
	```

### Running Tests
```sh
mvn test
```

## Project Structure
```
src/
  main/
	 java/com/scm/           # Java source code
	 resources/
		static/               # Static assets (CSS, JS, images)
		templates/            # Thymeleaf HTML templates
  test/
	 java/com/scm/           # Test classes
```

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)

---
### Canvas Link (for reference):
https://excalidraw.com/#json=SIuQrQnGQr9DGkCVc8BWD,JqVceoohF0UsTfllkzdRmw

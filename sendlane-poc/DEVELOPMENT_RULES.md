# Development Rules and Standards

## Language Standards
- **All code must be written in English**
  - Variable names, function names, class names
  - Comments and documentation
  - HTML content and user interface text
  - Console logs and error messages
  - API endpoints and parameters

## Code Style Guidelines
- Use descriptive, English variable names (e.g., `customEventData`, `emailAddress`)
- Comments should explain the "why", not the "what"
- Use consistent naming conventions (camelCase for JavaScript)
- All user-facing text must be in English

## Documentation Requirements
- README files in English
- Code comments in English
- API documentation in English
- Commit messages in English

## Examples
### ✅ Good (English)
```javascript
// Load Sendlane script
const customEventData = {
  "custom_event": "user_signup",
  "email": emailAddress
};
console.log('Custom event sent successfully');
```

### ❌ Bad (Spanish)
```javascript
// Cargar script de Sendlane
const datosEventoCustom = {
  "custom_event": "registro_usuario",
  "email": correoElectronico
};
console.log('Evento custom enviado exitosamente');
```

## Rationale
- Maintains consistency across international development teams
- Improves code readability for global contributors
- Aligns with industry standards and best practices
- Facilitates easier maintenance and debugging
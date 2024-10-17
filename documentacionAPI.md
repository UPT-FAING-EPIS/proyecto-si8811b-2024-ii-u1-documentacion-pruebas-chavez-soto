# Documentación de la API

## Autenticación

### POST /api/v1/auth/login
Inicia sesión de un usuario.

**Request Body:**
```json
{
  "email": "string",
  "password": "string"
}
```

**Response:**
```json
{
  "token": "string",
  "user": {
    "id": "string",
    "email": "string",
    "role": "string"
  }
}
```

### POST /api/v1/auth/register
Registra un nuevo usuario.

**Request Body:**
```json
{
  "email": "string",
  "password": "string",
  "role": "string"
}
```

**Response:**
```json
{
  "message": "User registered successfully",
  "user": {
    "id": "string",
    "email": "string",
    "role": "string"
  }
}
```

## Asistencia

### POST /api/v1/attendance/record
Registra la asistencia de un estudiante.

**Request Body:**
```json
{
  "classId": "string",
  "studentId": "string",
  "status": "string"
}
```

**Response:**
```json
{
  "message": "Attendance recorded successfully",
  "attendance": {
    "id": "string",
    "classId": "string",
    "studentId": "string",
    "status": "string",
    "date": "string"
  }
}
```

### GET /api/v1/attendance/student/{studentId}
Obtiene el registro de asistencia de un estudiante.

**Response:**
```json
{
  "studentId": "string",
  "attendanceRecords": [
    {
      "id": "string",
      "classId": "string",
      "status": "string",
      "date": "string"
    }
  ]
}
```

## Reportes

### GET /api/v1/reports/course/{courseId}
Genera un reporte de asistencia para un curso.

**Response:**
```json
{
  "courseId": "string",
  "courseName": "string",
  "attendanceRate": "number",
  "studentRecords": [
    {
      "studentId": "string",
      "studentName": "string",
      "attendanceRate": "number"
    }
  ]
}
```

# HECHO POR: CESAR FABIAN CHAVEZ LINARES

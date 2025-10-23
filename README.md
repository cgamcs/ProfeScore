## Ejemplos de Configuración de Variables de Entorno

### Backend (.env)

#### Desarrollo
```env
DATABASE_URL=mongodb+srv://profedb:<password>@cluster0.mtyzq.mongodb.net/profescore
FRONTEND_URL=http://localhost:5173
BACKEND_URL=http://localhost:4000
SECRET_KEY=6Leyxxxxxxxxxxxxxx
JWT_SECRET=palabrasupersecreta
```

### Frontend (.env)

#### Desarrollo
```env
VITE_SITE_KEY=6Leyxxxxxxxxxxxxxx
VITE_API_URL=http://localhost:4000/api
VITE_BACKEND_URL=http://localhost:4000
VITE_PUBLIC_KEY=oExxxxxxxxxxxxxxxxx
```
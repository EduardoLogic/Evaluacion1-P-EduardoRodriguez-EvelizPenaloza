# REPÚBLICA BOLIVARIANA DE VENEZUELA
# UPT DEL ESTADO ARAGUA "FEDERICO BRITO FIGUEROA"
# INFORMÁTICA - PROGRAMACIÓN II

**Integrantes:**
* Eduardo Rodriguez 27712316
* Evelys Peñaloza 18165953

**Enunciado Asignado:**
* **Enunciado 3: Concesionario de Vehículos** (Gestión de la entidad Vehículo con Placa, Modelo, Precio de Venta y Estado).

---

#### Instrucciones para ejecutar el proyecto

Para levantar este proyecto en un entorno local, siga estos pasos:
1. Clonar el repositorio:
   `git clone [git clone https://github.com/EduardoLogic/Evaluacion1-P-EduardoRodriguez-EvelizPenaloza.git]`
2. Entrar a la carpeta:
   `cd nombre-de-la-carpeta`
3. Instalar dependencias:
   `composer install`
   `npm install`
4. Configurar el entorno:
   - Copiar el `.env.example` a `.env`
   - Generar la clave: `php artisan key:generate`
5. Migrar la base de datos:
   `php artisan migrate --seed`
6. Ejecutar el servidor:
   `php artisan serve`


Ahora abre el navegador y pon esta dirección: http://127.0.0.1:8000/vehiculos

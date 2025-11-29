# MHOLLY - E-commerce de Prótesis 3D

<div align="center">
  <img src="./assets/mholly-banner.png" alt="MHOLLY Banner" width="100%">
  <br><br>
  <img src="https://img.shields.io/badge/Enfoque-Fintech_&_Pagos-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Colaboración-Pareja_(50/50)-blue?style=for-the-badge" />
</div>

## Descripción
Plataforma de venta de prótesis para mascotas con personalización de producto y gestión de pacientes.

## Mi Rol: Integración Fintech & Lógica
Desarrollado en **pareja (Participación Igualitaria)**. Mi enfoque fue:
- **Pagos:** Integración de **PayPal SDK** y **MercadoPago SDK**.
- **Seguridad:** Implementación de **2FA** y verificación de identidad.
- **Lógica:** Flujo de "Pedido Inmediato" vs "Pedido Diferido".
- **Comunicación:** Chat asíncrono Cliente-Admin.

## Stack Tecnológico Completo

**Backend & Seguridad**
- Laravel 12.0
- PHP 8.2
- Laravel Fortify (Autenticación Avanzada)
- Google2FA (Autenticación de dos factores)
- Eloquent ORM

**Integraciones & APIs**
- PayPal SDK (srmklive/paypal)
- MercadoPago SDK (mercadopago/dx-php)
- Mailtrap (Sistema de Notificaciones)

**Frontend**
- Livewire Flux 2.1
- Livewire Volt 1.7
- Chart.js (Visualización de datos)
- Blade Heroicons
- TailwindCSS

**Testing & Calidad**
- Pest 4.1
- PHPUnit
- Laravel Pint (Code Styling)

## Capturas
<div align="center">
  <img src="./assets/pagos.png" width="45%">
  <img src="./assets/dashboard-ventas.png" width="45%">
</div>

[Volver](../README.md)
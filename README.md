// ============================================
//   EJERCICIO 2: Trazabilidad de un Sistema
// ============================================

// Variables del sistema
let modulo = "Autenticación";
let intentosFallidos = 5;

// Generación de la alerta de seguridad (concatenación)
let alerta = "⚠️ ALERTA DE SEGURIDAD | Módulo: " + modulo + " | Intentos fallidos: " + intentosFallidos;

// Mostrar en consola
console.log("===========================================");
console.log("       SISTEMA DE TRAZABILIDAD - LOG       ");
console.log("===========================================");
console.log(alerta);
console.log("===========================================");

// Información adicional del log
let timestamp = new Date().toLocaleString("es-CO");
let logCompleto = "📋 LOG | Fecha: " + timestamp + " | " + alerta + " | Estado: BLOQUEADO";

console.log(logCompleto);

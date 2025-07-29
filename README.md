Hunt the Wumpus - Implementación Mejorada en Prolog
Descripción
Implementación avanzada del clásico juego Hunt the Wumpus con sistema de inferencia lógica y agente inteligente autónomo.
Características Implementadas
Sistema de Inferencia Avanzado
Se desarrolló un motor de inferencia que analiza percepciones y deduce información sobre peligros. El sistema elimina pozos posibles cuando no hay brisa y confirma ubicaciones cuando solo existe una explicación lógica posible.
Agente Inteligente
Se implementó un agente autónomo con estrategia jerárquica de toma de decisiones que prioriza celdas seguras, calcula riesgos y usa la flecha estratégicamente cuando es necesario.
Cálculo de Probabilidades
Se agregó un sistema que calcula probabilidades de peligro para cada celda basado en percepciones adyacentes y conocimiento previo.
Base de Conocimiento Dinámica
El agente mantiene registro de celdas visitadas, seguras, peligrosas y posibles ubicaciones de amenazas, actualizando constantemente su conocimiento.
Uso
?- resolver_inteligente.     % Ejecutar agente automático
?- estado_detallado.         % Ver estado completo
?- mostrar_conocimiento.     % Ver base de conocimiento
?- mostrar_mapa.            % Visualizar mapa
?- reiniciar.               % Reiniciar partida
Requisitos
SWI-Prolog
Archivos

wumpus.pl - Implementación principal del juego

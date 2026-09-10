# Reglas para trabajar el CRM (Base_Simbiosis.xlsx)

## Universo
- 10,913 oportunidades únicas, 2019 a 2026.
- Hoja DETALLE: 5,904 Elegible, 3,698 Excluida, 1,311 Revisar.
- Última actualización máxima registrada: 2026-08-12.

## Reglas de uso
- Usa ÚNICAMENTE Decisión = Elegible para sustentar casos ganados y perdidos.
- Excluida y Revisar no entran en resultados seleccionados. Si detectas una
  clasificación dudosa, repórtala; no la cambies en silencio.
- Conserva el Opportunity Number para trazabilidad.
- Tasa de ganancia = Won / (Won + Lost). Open queda fuera del denominador.
- NO EXISTE campo de motivo de pérdida. Si no está documentado, escribe
  "motivo no disponible". Nunca infieras la causa a partir del estatus Lost.
- Los montos MXN son potencial anual registrado. No sumes oportunidades
  recurrentes como demanda incremental sin revisarlas: hay importes idénticos
  repetidos entre años.
- La hoja DETALLE contiene oportunidades, no ventas facturadas.

## Datos que faltan en la base
- 820 registros Elegible sin Región CRM.
- 167 registros Elegible con importe en cero.
- 21 registros Elegible con Mercado = "#Please Specify#".
- Acentos y Ñ aparecen corruptos en Cliente clave y Oportunidad: usa búsquedas
  tolerantes (por ejemplo PE.A COLORADA para Peña Colorada).

## Clasificaciones dudosas detectadas (reportadas, NO modificadas)
1. 711934 · JUGOS DEL VALLE - LAGOS · Excluida por ID 2.1 aunque es planta de
   usuario final en Jalisco; además quedó en Región 38, no 32.
2. 539375 · CEMEX CONCRETOS GUADALAJADA · la clave dice Guadalajara pero la
   oportunidad y la región describen Hermosillo. Contamina el conteo de R32.
3. O-00190156 · SUKARNE CORP · único registro que toca la unidad de Culiacán,
   excluido por ID 4.1.
4. 767126 · CEMEX ZAPOTILTIC · tipo "apertura de sucursal" sobre una planta que
   opera desde hace décadas.
5. 546092 y 793657 · INGENIO LAZARO CARDENAS TARETAN · mismos casos.
6. 668485 · INGENIO QUESERIA · mismo caso.
7. O-00222959 y O-00238069 · ARCA CONTINENTAL TLAQUEPAQUE · los nombres de
   oportunidad se refieren a otras plantas.
8. Mercado inconsistente dentro de la misma cuenta: Ingenio Tala aparece como
   Manufacturing y como Food & Beverage; CEMEX Zapotiltic como Manufacturing y
   Construction; Peña Colorada como Mining.

## Claves duplicadas por familia (no fusionar sin confirmar)
SuKarne bajo 6 claves, CEMEX bajo 17, ArcelorMittal bajo 5, Smurfit bajo 4.
NO confundir: LA PITALLA - LA COLORADA y PLATA PANAMERICANA - MINA LA COLORADA
NO son Peña Colorada.

## Responsables marcados como inactivos en la base
Froylan Santiago Alcántara, Jonathan Gómez, Johnatan Murillo, Alejandro Escobedo
Meza, Felipe Jiménez, Abel Valenzuela, Armando Hernández, Jesús Bazúa, Carlos Raúl
Trejo. No les asignes trabajo. Primero hay que designar quién recupera el expediente.

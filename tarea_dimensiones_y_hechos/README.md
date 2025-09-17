# Dimnesiones 


## Dimensiones hechas por @camiloacr1322:

### ID investigadores

Se seleciona la columna de ID_PERSONA_PR en la base de investigadores consolidados hecha anteriormente por grupo.
Ya se tiene ID por investigador en la base, por lo cual no se crea uno.

### Id de la convocatoria 

Se selciona la columna de ID_CONVOCATORIA en la base de investigadores consolidados hecha anteriormente por grupo.
Ya se tiene ID por convocatoria en la base, por lo cual no se crea uno.

### Codigo del Dane por municipio de Nacimineto

Se selciona la columna de COD_DANE_NAC_PR en la base de investigadores consolidados hecha anteriormente por grupo.
Ya se tiene el codigo del Dane por municipio en la base, por lo cual no se crea uno.

---

### 2. Dimensión **Universidad**
- Se crea a partir de la columna `INST_FILIA`.  
- Se creó un identificador único para cada universidad, se eliminaron de nulos y duplicados.

**Resultado:** 2.983 universidades 

---

### 3. Dimensión **Nivel de Formación**
- Columnas utilizadas:
  - `ID_NIV_FORMACION_PR` (id del nivel).  
  - `NME_NIV_FORM_PR` (nombre del nivel).  
  - `NRO_ORDEN_FORM_PR` (jerarquía).  
- Se eliminaron duplicados y valores faltantes.  

**Resultado:** 11 niveles de formación  

---

### 4. Dimensión **Residencia**
- Columnas utilizadas:
  - `COD_DANE_RES_PR` (código DANE).  
  - `NME_PAIS_RES_PR` (país).  
  - `NME_REGION_RES_PR` (región).  
  - `NME_DEPARTAMENTO_RES_PR` (departamento).  
  - `NME_MUNICIPIO_RES_PR` (municipio).  

**Resultado:** 224 combinaciones únicas 

Se exportan las tablas a un archivo **Excel** `dimensiones_investigadores.xlsx`.

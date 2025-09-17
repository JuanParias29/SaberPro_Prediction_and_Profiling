# 📖 Diccionario de Datos – Resultados únicos Saber Pro

A continuación, se presenta una tabla descriptiva de los campos del conjunto de datos **Resultados únicos Saber Pro**.

| Nombre del Campo              | Tipo de Dato               | Descripción de Negocio |
|-------------------------------|----------------------------|------------------------|
| PERIODO                       | Entero (año/semestre)      | Indica la cohorte de aplicación de la prueba; permite analizar tendencias temporales y comparar periodos académicos. |
| ESTU_CONSECUTIVO              | Identificador (texto)      | Código único del estudiante en el examen; solo para trazabilidad, no se usa como variable predictora. |
| ESTU_TIPODOCUMENTO            | Categórica nominal         | Tipo de documento de identidad; útil solo para validar registros, no para el modelo predictivo. |
| ESTU_PAIS_RESIDE              | Categórica nominal         | País de residencia del examinando. |
| ESTU_COD_RESIDE_DEPTO         | Categórica nominal (código)| Permite segmentar estudiantes por departamento de residencia y analizar diferencias territoriales de desempeño. |
| ESTU_DEPTO_RESIDE             | Categórica nominal         | Departamento de residencia del estudiante. |
| ESTU_COD_RESIDE_MCPIO         | Categórica nominal (código)| Municipio de residencia (código). |
| ESTU_MCPIO_RESIDE             | Categórica nominal         | Municipio de residencia. |
| ESTU_CODDANE_COLE_TERMINO     | Categórica nominal (código)| Código Dane del colegio donde se graduó. |
| ESTU_COD_COLE_MCPIO_TERMINO   | Categórica nominal (código)| Municipio donde terminó bachillerato. |
| ESTU_COD_DEPTO_PRESENTACION   | Categórica nominal (código)| Código del departamento de presentación del examen. |
| INST_COD_INSTITUCION          | Categórica nominal (código)| Código de la Institución de Educación Superior. |
| INST_NOMBRE_INSTITUCION       | Categórica nominal         | Nombre de la Institución de Educación Superior. |
| INST_CARACTER_ACADEMICO       | Categórica nominal         | Carácter académico de la institución (Universidad, Tecnológica, etc.). |
| ESTU_NUCLEO_PREGRADO          | Categórica nominal         | Núcleo del pregrado; permite estudiar variaciones en puntajes por área. |
| ESTU_INST_DEPARTAMENTO        | Categórica nominal         | Departamento de la Institución de Educación Superior. |
| ESTU_INST_CODMUNICIPIO        | Categórica nominal (código)| Código del municipio de la institución. |
| ESTU_INST_MUNICIPIO           | Categórica nominal         | Municipio de la institución. |
| ESTU_PRGM_ACADEMICO           | Categórica nominal         | Programa académico cursado. |
| ESTU_PRGM_DEPARTAMENTO        | Categórica nominal         | Departamento del programa académico. |
| ESTU_PRGM_CODMUNICIPIO        | Categórica nominal (código)| Código del municipio del programa académico. |
| ESTU_PRGM_MUNICIPIO           | Categórica nominal         | Municipio del programa académico. |
| ESTU_NIVEL_PRGM_ACADEMICO     | Categórica nominal         | Nivel del programa académico. |
| ESTU_METODO_PRGM              | Categórica nominal         | Metodología del programa (Presencial, Distancia, etc.). |
| ESTU_VALORMATRICULAUNIVERSIDAD| Categórica ordinal         | Valor de la matrícula de la universidad. |
| ESTU_DEPTO_PRESENTACION       | Categórica nominal         | Departamento de presentación del examen. |
| ESTU_COD_MCPIO_PRESENTACION   | Categórica nominal (código)| Código del municipio de presentación del examen. |
| ESTU_MCPIO_PRESENTACION       | Categórica nominal         | Municipio de presentación del examen. |
| ESTU_PAGOMATRICULABECA        | Binario (Sí/No)            | ¿Paga matrícula con beca? |
| ESTU_PAGOMATRICULACREDITO     | Binario (Sí/No)            | ¿Tiene crédito para pagar matrícula? |
| ESTU_HORASSEMANATRABAJA       | Categórica ordinal         | Horas de trabajo semanales. |
| ESTU_SNIES_PRGMACADEMICO      | Categórica nominal (código)| Código SNIES del programa académico. |
| ESTU_PRIVADO_LIBERTAD         | Binario (Sí/No)            | ¿Es privado de la libertad? |
| ESTU_NACIONALIDAD             | Categórica nominal         | Nacionalidad del estudiante. |
| ESTU_ESTUDIANTE               | Categórica nominal         | Identifica condición de estudiante (irrelevante). |
| ESTU_GENERO                   | Categórica nominal         | Género del estudiante (M/F). |
| ESTU_COLE_TERMINO             | Categórica nominal         | Colegio donde terminó bachillerato. |
| ESTU_PAGOMATRICULAPADRES      | Binario (Sí/No)            | ¿Los padres pagan la matrícula? |
| ESTU_ESTADOINVESTIGACION      | Categórica nominal         | Estado de investigación (irrelevante, siempre “PUBLICAR”). |
| ESTU_FECHANACIMIENTO          | Fecha                      | Fecha de nacimiento, usada para calcular la edad al momento del examen. |
| ESTU_PAGOMATRICULAPROPIO      | Binario (Sí/No)            | ¿El estudiante paga la matrícula por sí mismo? |
| ESTU_TIPODOCUMENTOSB11        | Categórica nominal         | Tipo de documento usado en Saber 11. |
| FAMI_EDUCACIONPADRE           | Categórica ordinal         | Nivel de estudios del padre. |
| FAMI_TIENEAUTOMOVIL           | Binario (Sí/No)            | ¿La familia tiene automóvil? |
| FAMI_TIENELAVADORA            | Binario (Sí/No)            | ¿La familia tiene lavadora? |
| FAMI_ESTRATOVIVIENDA          | Categórica ordinal         | Estrato socioeconómico. |
| FAMI_TIENECOMPUTADOR          | Binario (Sí/No)            | ¿La familia tiene computador? |
| FAMI_TIENEINTERNET            | Binario (Sí/No)            | ¿La familia tiene acceso a internet? |
| FAMI_EDUCACIONMADRE           | Categórica ordinal         | Nivel de estudios de la madre. |
| INST_ORIGEN                   | Categórica nominal         | Origen de la institución (oficial, no oficial, etc.). |
| MOD_RAZONA_CUANTITAT_PUNT     | Numérico continuo          | Puntaje en Razonamiento Cuantitativo. |
| MOD_COMUNI_ESCRITA_PUNT       | Numérico continuo          | Puntaje en Comunicación Escrita. |
| MOD_COMUNI_ESCRITA_DESEM      | Numérico ordinal           | Desempeño en Comunicación Escrita (1, 2, 3). |
| MOD_INGLES_DESEM              | Categórica ordinal         | Nivel de desempeño en Inglés. |
| MOD_LECTURA_CRITICA_PUNT      | Numérico continuo          | Puntaje en Lectura Crítica. |
| MOD_INGLES_PUNT               | Numérico continuo          | Puntaje en Inglés. |
| MOD_COMPETEN_CIUDADA_PUNT     | Numérico continuo          | Puntaje en Competencias Ciudadanas. |
| PUNTAJE_GLOBAL                | Numérico continuo          | Puntaje global obtenido en la prueba Saber Pro. |
| PERCENTIL_GLOBAL              | Numérico continuo          | Percentil global obtenido en la prueba Saber Pro. |

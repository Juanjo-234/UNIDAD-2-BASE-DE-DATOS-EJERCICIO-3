# UNIDAD-2-BASE-DE-DATOS-EJERCICIO-3
Se debe diseñar un modelo entidad-relación (MER) para representar el funcionamiento de una institución médica, organizando la información de los pacientes, médicos, especialidades, turnos y medicamentos.

El sistema debe permitir registrar:
- Pacientes: número de historia clínica, DNI, nombre, apellido, fecha de nacimiento, domicilio y obra social.
- Médicos: matrícula profesional, nombre, teléfono y especialidades que poseen.
- Especialidades: registrar la especialidad principal y las secundarias de cada médico.
- Turnos: relacionan a un paciente con un médico y almacenan la fecha, hora, estado y diagnóstico u observación preliminar.
- Medicamentos: código, nombre comercial, monodroga y laboratorio fabricante.
- Prescripciones: relacionan los turnos con los medicamentos recetados e indican la dosis, frecuencia y duración del tratamiento.
También se deben establecer las relaciones y cardinalidades, teniendo en cuenta que un paciente puede tener varios turnos, un médico puede tener varias especialidades y en una misma consulta se pueden recetar varios medicamentos.

El objetivo es crear un MER que permita organizar y administrar la información médica, los turnos de atención y las recetas de los pacientes de forma clara y ordenada.

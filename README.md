# KeepCodingSqlEjerc1
Diagrama de Entidad Relacion
Las entidades creadas fueron: student, bootcamp. module, teacher y la tabla inscription.
Y las Relaciones establecidas fueron las siguientes:

* student-bootcamp: La relación es de muchos a muchos y para ello se creó la tabla inscripción para manejar la relación de muchos a muchos entre student y bootcamp (student_id, bootcamp_id).
Un student puede inscribirse en más de un bootcamp y
Un bootcamp puede tener a varios student.

* bootcamp-module: La relación es de uno a muchos desde bootcamp a module. Un bootcamp puede incluir múltiples module, y un módule pertenece a un bootcamp.
Un bootcamp puede tener varios module
Un module puede pertenecer a un sólo bootcamp

* module-teacher: Uno a muchos desde module a teacher. Un module tine un teacher y un teacher puede impartir varios module.
  Un module puede ser impartido por un teacher, y
  Un teacher puede impartir múltiples  module.

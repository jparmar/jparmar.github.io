jparmar.github.io
=================

Justin Parmar

ROR:
MOdel ralation with condition
has_many :reports, -> { where(template: false) }, :class_name => 'CustomReport', :foreign_key => 'parent_id'

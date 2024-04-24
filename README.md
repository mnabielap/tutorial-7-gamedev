# Tutorial 7

> Sprinting & crouching

Dengan fitur ini, player dapat berlari dan berjalan dan juga dengan cara crouch.

Caranya adalah dengan melakukan penambahan pada script godot.
```py
	if Input.is_action_pressed("run"):
		movement_vector = movement_vector * run_variable
	elif Input.is_action_pressed("crouch"):
		movement_vector = movement_vector * crouch_variable
```

Run: Shift dan Crounch: Ctrl

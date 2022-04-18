# useForm Hook

Ejemplo de uso

```
    const initialForm = {
        name: 'nombre',
        email: 'correo@mail.com',
        ...
    };

    const [ formValues, handleInputChange, reset ] = useForm(initialForm);
```
# Módulo Frontend

La interfaz de usuario del dashboard de métricas está construida con **React** y **TypeScript**.

## Implementación de Componentes

A continuación, puedes ver cómo se inicializa el estado y la vista del componente principal:

=== "TypeScript"
    ```typescript
    import React, { useState, useEffect } from 'react';

    export const MetricsWidget: React.FC = () => {
        const [data, setData] = useState<number[]>([]);

        useEffect(() => {
            console.log("Cargando métricas...");
        }, []);

        return <div>Widget Cargado</div>;
    }
    ```

=== "JavaScript"
    ```javascript
    import React, { useState, useEffect } from 'react';

    export const MetricsWidget = () => {
        const [data, setData] = useState([]);

        useEffect(() => {
            console.log("Cargando métricas...");
        }, []);

        return <div>Widget Cargado</div>;
    }
    ```
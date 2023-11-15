'''mermaid

sequenceDiagram

Browser->>Server: Evento de envio de formulario

Server-->>Browser: HTTP 302 (redireccion URL)

note over Browser: Recargar la pagina de notes

Browser->>Server: Solicitud para obtener main.css

Browser->>Server: Solicitud para obtener main.js

Browser->>Server: Solicitud para obtener data.json

Server-->>Browser: Crea un nuevo objeto de nota y lo agrega a un arreglo llamado "notes"

end

'''

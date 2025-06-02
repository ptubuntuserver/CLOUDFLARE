# CLOUDFLARE
Pasos para el uso de cloudflare sobre dominios
<p>
    <strong>Paso 1</strong>
</p>
<p>
    Crear una cuenta y agregar el dominio al cloudflare
</p>
<p>
    <strong>Paso 2</strong>
</p>
<p>
    Agregar los DNS de cloudflare por los 2 servidores DNS de Cloudflare en el panel del Dominio.
</p>
<p>
    <strong>Paso 3</strong>
</p>
<p>
    Ingresar los registros en el panel donde se debe integrar todos los registros ( email, ftp, www.odoo.zabbix,etc)
</p>
<p>
    Activar el proy sólo para servicios web (excluir correo)
</p>
<p>
    Los demás dejar que se resuelvan a como esta en el panel de zona del dominio ya configurado.
</p>
<p>
    &nbsp;
</p>
<p>
    Si hay problemas con los ssl , configurar en el cloudflare el servicio Flexible en vez del full que esta por defecto.
</p>
<p>
    &nbsp;
</p>
<p>
    <code>Estos cambios pueden tomar de 24 horas hasta 72 horas.</code>
</p>

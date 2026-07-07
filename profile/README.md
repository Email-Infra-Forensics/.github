<div align="center">
  <img src="./components/banner.svg" width="100%" alt="Email-Infra-Forensics Header" />
</div>

<br />

<div align="center">

> **Email-Infra-Forensics** es un colectivo y ecosistema Open-Source especializado en la auditoría estructural y validación forense de infraestructuras de correo electrónico. Proveemos herramientas para curación de datos ( $\color{#ec4899}{\textsf{Data Ingestion}}$ ), análisis de topología ( $\color{#8b5cf6}{\textsf{Traceroute y ASN}}$ ), validación criptográfica ( $\color{#ec4899}{\textsf{SPF/DKIM/DMARC}}$ ) y generación de firmas algorítmicas mediante huellas digitales de infraestructura ( $\color{#8b5cf6}{\textsf{Email Trust Index}}$ ).

</div>

<br />

## <img src="./components/icon-vector.svg" width="28" height="28" align="top" /> Vectores de Investigación

<div align="center">
<table width="100%">
  <tr>
    <td align="center" width="25%">
      <img src="./components/icon-data.svg" width="48" alt="Data Curation" />
      <br />
      <strong>Data Curation & ETL</strong>
    </td>
    <td align="center" width="25%">
      <img src="./components/icon-forensics.svg" width="48" alt="Forensic Analysis" />
      <br />
      <strong>Forensic Engine</strong>
    </td>
    <td align="center" width="25%">
      <img src="./components/icon-topology.svg" width="48" alt="Topology Analysis" />
      <br />
      <strong>Topology Analysis</strong>
    </td>
    <td align="center" width="25%">
      <img src="./components/icon-client.svg" width="48" alt="Client Integrations" />
      <br />
      <strong>Client Integrations</strong>
    </td>
  </tr>
</table>
</div>

<br />

## <img src="./components/icon-ecosystem.svg" width="28" height="28" align="top" /> Ecosistema de Repositorios

El núcleo del proyecto se divide en módulos arquitectónicos diseñados para operar de forma independiente o como una solución integral de análisis de amenazas.

### Motores y Backend
- <img src="./components/icon-core.svg" width="20" height="20" align="top" /> **[Core Framework](https://github.com/Email-Infra-Forensics/core-framework)** - El motor forense central (*ETI Engine*) construido en Python/FastAPI. Realiza el procesamiento de cabeceras, consultas RDAP en caché y validación criptográfica.
- <img src="./components/icon-data-curator.svg" width="20" height="20" align="top" /> **[Data Curator](https://github.com/Email-Infra-Forensics/data-curator)** - Pipeline de ingesta diseñado para limpiar y anonimizar datasets masivos de correo electrónico mediante técnicas de *hashing* criptográfico SHA-256.

### Interfaces y Extensiones
- <img src="./components/icon-thunderbird.svg" width="20" height="20" align="top" /> **[Thunderbird Validator](https://github.com/Email-Infra-Forensics/thunderbird-validator)** - Extensión para clientes de correo (Mozilla Thunderbird) que se conecta con el *Core Framework* para analizar los emails en tiempo real y emitir veredictos visuales para el usuario final.
- <img src="./components/icon-web.svg" width="20" height="20" align="top" /> **[Web Dashboard](https://github.com/Email-Infra-Forensics/web-email-validator-priv)** - Plataforma web interactiva para la visualización de métricas globales y perfiles organizacionales basados en el ETI (*Email Trust Index*).

### Investigación y Academia
- <img src="./components/icon-docs.svg" width="20" height="20" align="top" /> **[Documentation](https://github.com/Email-Infra-Forensics/documentation)** - Documentación técnica y académica del proyecto, incluyendo el fundamento forense, investigación de infraestructuras, bases de datos y la bitácora de desarrollo.

<br />
<hr />

<div align="center">
  <h2><img src="./components/icon-target.svg" width="32" height="32" align="top" /> Propósito Organizacional</h2>
  <p><i>Email-Infra-Forensics está dedicado a la investigación activa del enrutamiento de correos corporativos. Buscamos unificar las capas de seguridad criptográfica con la trazabilidad forense para detectar anomalías, suplantación y campañas fraudulentas mucho antes de que comprometan al usuario final.</i></p>
  
  <br />
  
  <p>
    <a href="https://github.com/Email-Infra-Forensics/core-framework">Engine</a> |
    <a href="https://github.com/Email-Infra-Forensics/documentation">Docs</a> |
    <a href="https://github.com/Email-Infra-Forensics/web-email-validator-priv">Web</a>
  </p>
</div>
# Instrucciones de Configuración

Este proyecto utiliza Yarn como gestor de paquetes y TypeScript para la programación. A continuación se detallan los comandos utilizados para la configuración inicial del proyecto:

```bash
# 1. Inicializar un nuevo proyecto de Yarn
yarn init -y

# 2. Instalar TypeScript como una dependencia de desarrollo
yarn add typescript -D

# 3. Crear un archivo de configuración de TypeScript
yarn run tsc --init

# 4. Instalar las herramientas necesarias para gRPC y TypeScript
yarn add ts-node grpc-tools @types/google-protobuf grpc_tools_node_protoc_ts -D
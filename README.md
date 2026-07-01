# Kubernetes Hands-On

Este repositorio contiene ejemplos prácticos de Kubernetes organizados por tema, incluyendo manifests YAML para Pods, Deployments, Services, ConfigMaps, Secrets, Namespaces, Resource Quotas, Limits, Probes y más.

## Contenido

- ConfigMaps y ejemplos de configuración
- Deployments y ReplicaSets
- Servicios y exposiciones de aplicaciones
- Recursos y límites de CPU/ memoria
- Namespaces y ambientes
- Probes de salud y manejo de contenedores
- Ejemplos de variables de entorno

## Requisitos

- Kubernetes instalado y configurado
- kubectl disponible
- Un cluster local o remoto accesible

## Uso

Aplicar un manifiesto:

```bash
kubectl apply -f <archivo.yaml>
```

Verificar recursos:

```bash
kubectl get pods
kubectl get svc
kubectl get deployments
```

Eliminar un recurso:

```bash
kubectl delete -f <archivo.yaml>
```

## Objetivo

Este repositorio sirve como material de estudio para aprender Kubernetes de forma práctica, con ejemplos sencillos y organizados.

## Autor

Ricardo / Robbhedonic

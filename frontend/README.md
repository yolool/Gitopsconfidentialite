This folder contains Kubernetes manifests for the frontend service (frontend-confidentielity).

Usage:
  # Apply frontend manifests
  kubectl apply -k ./gitops/frontend

Notes:
  - Replace the image in deployment.yaml with your image (your-registry/frontend-confidentielity:tag).
  - Update resource requests/limits as needed.

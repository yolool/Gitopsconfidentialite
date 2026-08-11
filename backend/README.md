This folder contains Kubernetes manifests for the backend service (backend-confidentielity).

Usage:
  # Apply backend manifests
  kubectl apply -k ./gitops/backend

Notes:
  - Replace the image in deployment.yaml with your image (your-registry/backend-confidentielity:tag).
  - Update resource requests/limits as needed.

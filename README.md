This version spins in addition to the scica-live containers, an api wrapper (myscicat_api_scripts) that can be used to add datasets and oridatasets as: 
docker exec -it myscicat_api_scripts /app/entrypoint.sh create dataset /app/data/metadata.json

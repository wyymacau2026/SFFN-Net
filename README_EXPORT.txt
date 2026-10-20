CPU-only compact snapshot; no training or inference was performed.
No images, prediction masks, metrics, or statistical result tables are included.
Each model is seed42/model_best only, exported without optimizer or score history.
Tensor values/dtypes are retained exactly; these are NOT resume-training checkpoints.
Load the weights with model.load_state_dict(torch.load(path, map_location="cpu")["state_dict"]).
Keep the supplied .model.pkl/plans.pkl as legacy architecture/planning metadata.
Current code and reference launchers are a snapshot, not a certified clean-room reproduction.
Resolve launcher paths and verify the correct Full/identity-FFN architecture before inference.
No data licence or source licence is replaced. Review identity/secrets before sharing.
Download only the files in download/. Keep manifest.json with the parts.
Reassemble each archive in manifest order, verify its SHA256, then extract.

PM Kimiagaran — LOCAL deployment registry (simulates private GitHub raw URL)
=============================================================================

This folder is your LOCAL registry. In production, use a private GitHub/GitLab repo
with the same JSON file at raw URL.

Serve locally:
  bash ../pm_kimiagaran_v1/scripts/serve_local_deploy_registry.sh

Raw URL (for Odoo system parameter):
  http://127.0.0.1:8765/pm_kimiagaran_v1_deployments.json

Sync this server's fingerprint from Odoo test DB:
  bash ../pm_kimiagaran_v1/scripts/sync_local_fingerprint.sh

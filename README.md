# LINBIT Brand Assets

Source of truth for LINBIT brand logos and assets. Files in this repo are deployed to linbit.com/assets/brand/ and referenced by the Brand Resources page.

## Naming Convention

Files follow the pattern:

```
{product}-{logo|icon}-{variant}.{ext}
```

- **product** — `linbit`, `linbit-sds`, `linbit-ha`, `linbit-dr`, `linstor`, `drbd`
- **type** — `logo` or `icon`
- **variant** — `color`, `black`, or `white`
- **ext** — `svg` or `png`

Examples:

- `linbit-logo-color.svg`
- `linstor-logo-black.png`
- `linbit-icon-white.svg`

## File Manifest

### LINBIT Logo

- [ ] linbit-logo-color.svg
- [ ] linbit-logo-color.png
- [ ] linbit-logo-black.svg
- [ ] linbit-logo-black.png
- [ ] linbit-logo-white.svg
- [ ] linbit-logo-white.png

### LINBIT Icon

- [ ] linbit-icon-color.svg
- [ ] linbit-icon-color.png
- [ ] linbit-icon-black.svg
- [ ] linbit-icon-black.png
- [ ] linbit-icon-white.svg
- [ ] linbit-icon-white.png

### LINBIT SDS Logo

- [ ] linbit-sds-logo-color.svg
- [ ] linbit-sds-logo-color.png
- [ ] linbit-sds-logo-black.svg
- [ ] linbit-sds-logo-black.png
- [ ] linbit-sds-logo-white.svg
- [ ] linbit-sds-logo-white.png

### LINBIT HA Logo

- [ ] linbit-ha-logo-color.svg
- [ ] linbit-ha-logo-color.png
- [ ] linbit-ha-logo-black.svg
- [ ] linbit-ha-logo-black.png
- [ ] linbit-ha-logo-white.svg
- [ ] linbit-ha-logo-white.png

### LINBIT DR Logo

- [ ] linbit-dr-logo-color.svg
- [ ] linbit-dr-logo-color.png
- [ ] linbit-dr-logo-black.svg
- [ ] linbit-dr-logo-black.png
- [ ] linbit-dr-logo-white.svg
- [ ] linbit-dr-logo-white.png

### LINSTOR Logo

- [ ] linstor-logo-black.svg
- [ ] linstor-logo-black.png
- [ ] linstor-logo-white.svg
- [ ] linstor-logo-white.png

### DRBD Logo

- [ ] drbd-logo-black.svg
- [ ] drbd-logo-black.png
- [ ] drbd-logo-white.svg
- [ ] drbd-logo-white.png

### Archive

- [ ] linbit-brand-assets.zip (all of the above)

## Deployment

Files are deployed via SFTP to `/assets/brand/` on the LINBIT web server. The zip file should be regenerated whenever assets are added or updated.

## Notes

This repo may be migrated to LINBIT's internal GitLab instance in the future.

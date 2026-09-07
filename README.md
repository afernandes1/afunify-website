# afunify website

Static bilingual website for `afunify.com`, prepared for Netlify.

## Hosting model

- Website: Netlify
- Domain and DNS: OVH
- Email: Microsoft 365
- Voice AI applications and customer portals: AWS

## Deploy

1. Import this repository into Netlify.
2. Keep the build command empty and use `.` as the publish directory.
3. Add `afunify.com` as the primary custom domain and `www.afunify.com` as its alias.
4. Add only the website records requested by Netlify to the OVH DNS zone.
5. Preserve all Microsoft 365 MX, SPF, DKIM and DMARC records.


# Django Security Hardening

**Status:** Planned

Document a small Django application, its security-relevant settings, changes made, and validation.

## Checklist

- Keep debug mode disabled outside local development.
- Store secret configuration outside source control.
- Configure allowed hosts, HTTPS, secure cookies, and trusted origins appropriately for the deployment.
- Use Django's ORM and template escaping; validate input at trust boundaries.
- Apply authentication, authorization, CSRF protections, and least privilege.
- Keep dependencies supported and patched.

## Implementation record

- **Django / Python versions:**
- **Changes and rationale:**
- **Tests and results:**
- **Remaining limitations:**

Never commit secrets or production configuration.

---
version: 1
service:
  name: A ruby repo
  lifecycle: alpha
  tier: tier_1
  product: a
  owner:
  language: TypeScript
  framework: Django
  description: NIce
  aliases:
  tags:
  - key: backstage_kind
    value: component
  - key: ensure
    value: pass
  - key: hello
    value: world
  - key: lang
    value: ruby
  - key: reminder
    value: 'true'
  repositories:
  - name: derek-etherton/PsyKey
    path: "/"
    provider: github
    display_name: PsyKey (ruby version)
  tools:
  dependencies:
  - alias: a_service
    notes: aaaaaa
  alert_sources:
  - type: datadog
    external_id: '51809787'

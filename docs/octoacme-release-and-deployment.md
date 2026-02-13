# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. This guide should be used in conjunction with the [Release Readiness Checklist](templates/release-readiness-checklist.md) and coordinated by the Release Manager.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted by Technical Writer or Release Manager
- Rollback / mitigation plan documented by DevOps Engineer
- Smoke tests prepared by QA Lead
- Complete [Release Readiness Checklist](templates/release-readiness-checklist.md)

## Deployment Checklist
- [ ] Deployment window scheduled by Release Manager (if needed)
- [ ] Backup or snapshot completed by DevOps Engineer (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Lead sign-off)
- [ ] Deploy to production (automated pipeline preferred, executed by DevOps Engineer)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Release Manager coordinates)
- [ ] Technical Writer updates user-facing documentation

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer)
  - Rollback to last known-good release if necessary (executed by DevOps Engineer)
  - Triage root cause and capture action items (led by Release Manager and Project Manager)
  - Communicate status to stakeholders using incident communication template

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

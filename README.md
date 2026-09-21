# ElMex Ops

Current production source: **v1.9.12**

This repository is the source copy for the ElMex Ops manager app.

## v1.9.12 changes
- Shopping List +/- quantity controls let the manager adjust what will actually be purchased without changing inventory counts.
- The calculated inventory order quantity is retained as the suggested quantity and can be reset.
- New inventory items are inserted immediately after the current item instead of always going to the end.
- Existing v1.9.11 features remain, including Move Store, Quick Supplier Order, Firebase cloud sync, and ElMex Ops branding.

## Firebase
Firebase project: `el-mexican-inv-app`

Hosting source folder: `public`

A backup branch named `backup-before-elmex-ops-v1.9.12` preserves the repository state before this replacement.

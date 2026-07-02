# Yuan Tools Workspace Instructions

This is the master workspace for Yuan's mini tools.

## Required Structure

- Create every mini tool directly under `D:\dev\yuan-tools`.
- Use English ASCII project folders such as `yuan-image-redactor`.
- Use clear Chinese names in the actual tool UI and user-facing documentation.
- Keep each tool's project README at `yuan-*/README.md`.
- Do not copy tool `README.md` files into release folders.
- Copy the end-user guide into both `release/html` and `release/win`.
- Put final web builds in `release/html`.
- Put final Windows desktop artifacts in `release/win`.
- Configure Windows release EXEs as GUI applications so no terminal window appears.

## Registry

After creating, changing, or re-releasing a tool, update both root registry files:

- `TOOLS.md`
- `tools.json`

Keep `tools.json` valid JSON and preserve unrelated existing entries.

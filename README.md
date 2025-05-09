# DeepWiki Documentation Generator

This action automatically generates documentation from [DeepWiki](https://deepwiki.com/) using [deepwiki-md](https://github.com/he1senbrg/deepwiki-md).

**Note:** Your repository must already be indexed on [DeepWiki](https://deepwiki.com/) for this action to work.

## Steps
- Uses the `deepwiki-md` tool to extract the project's documentation from DeepWiki.
- Commits and pushes the updated docs back to the `docs/` directory in your repository.

## Usage

This workflow runs automatically on:
- Pushes to the `main` branch.
- Manual triggers.

## Output

Generated documentation will be stored in the `docs/` directory of the project repository.

## Disclaimer

This action is provided as-is, with no guarantees or warranties of any kind. I take no responsibility for how it is used, or any issues that may arise from its use.

If you use this action to generate documentation for your project, please include a credit to [DeepWiki](https://deepwiki.com/) in your project's README.

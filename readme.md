## Testing tap-bls

### Prerequisites

- meltano

### Setup

- Run `meltano install` which will install tap-bls and target-jsonl
- Create a `.env` file with `TAP_BLS_API_KEY=<your API key>`

### Testing

Run `meltano elt tap-bls target-jsonl` and inspect the contents of the `output` directory to confirm everything worked

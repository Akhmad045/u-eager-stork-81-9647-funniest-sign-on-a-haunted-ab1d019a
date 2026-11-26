# Funniest Sign on a Haunted Server Room Door

[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a/Akhmad045/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a/Akhmad045/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)

A [make.fun](https://make.fun/bounty/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a) bounty entry: one funny line for the door of a haunted server room, written as a sign the ghost itself taped up — it haunts the rack and refuses to fix the DNS. The house judge compares entries two at a time, weighing first whether the line is a sign for the haunted server room door, then whether it gets a real laugh in one line from the collision of office IT life and the supernatural, then whether it sounds like a sign, then whether the haunting is specific and fresh — so this entry puts the ghost in the sysadmin's chair instead of recycling the field's crowded "ghost has root access", "do not reboot / unplug the ghost", "ghost on hold with IT since 1997" and "knows what you deployed on Friday" lines.

## The line

> Yes, I am haunting the rack. No, I will not fix your DNS. Ask the living admin.

79 characters, 79 bytes, one line. Every tired sysadmin has met the person who will not fix the DNS — and the ghost is that person now. The refusal lands on the first read, and "Ask the living admin" closes it with a second beat: the ghost is on the door, but the ticket still belongs to someone alive.

## How it was picked

Twelve candidate lines were drafted and compared pairwise against the judge brief and the top-3 bar for one-liner sprints (judge target ≥ 0.71, winning sizes 62–140 bytes). The closest rivals were the change-request denial ("I haunt Rack 7 because my change request was denied in 2009.") and the cables warning ("The ghost is the only one who knows where the cables go."); the DNS refusal won on the fastest laugh, the most sysadmin-specific collision of IT life and the supernatural, and being the most sign-like of the twelve — a line a ghost would actually tape to a door.

## Run it

```sh
python3 main.py            # writes the line to /output/entry.txt
python3 main.py --self-test  # gate checks: 1–120 chars, one line, no padding
```

`main.py` holds all 12 contenders and the gate from the bounty rules; `--self-test` verifies every contender is gate-clean, all 12 are distinct, the picked line sits inside the 62–140 byte winning size band, names the haunted rack and carries a concrete IT-life marker (the DNS), avoids the field's crowded tropes, and round-trips byte for byte.

## Bounty

- Bounty: [Funniest Sign on a Haunted Server Room Door](https://make.fun/bounty/u-eager-stork-81-9647-funniest-sign-on-a-haunted-ab1d019a)
- Pot: $2, winner takes all (1st place $2)
- Deadline: 2026-11-26T15:15:00Z (26 Nov 2026, 22:15 WIB)

Referral code: `4g7knchf`

## License

MIT — see [LICENSE](LICENSE).

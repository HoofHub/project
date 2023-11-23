# HoofHub

## Target features

- [ ] Plan and track dates and tasks for breeding operations

  For example, calculating dates and reminders for:

  - When a mare should be teased again after a breeding
  - Due date range
  - Stopping fescue intake

- [ ] Tracking and reminders for care tasks, such as:

  - Vaccinations
  - Deworming
  - Farrier trims/shoes
  - Veterinary treatment
  - Custom care tasks

  Care tasks can be scheduled for an individual horse or multiple at a time.

- [ ] Ability to see any horse's care record and optionally share with others
- [ ] Store each horse's daily feed and supplement information, and keep track of when changes were made
- [ ] Add other team members to a farm

## Building HTML from `features.md`

```sh
mkdir -p out && cp -R assets out/
pandoc features.md -f gfm -t html -s -o out/index.html -c assets/simple.css
```

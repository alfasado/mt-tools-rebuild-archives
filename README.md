# About rebuild-archives for Movable Type

## Synopsis

The rebuild-archives script can be rebuild archives from the command line.

## Example

Execute from the command line.

    cd /path/to/mt; perl ./tools/rebuild-archives --at Index,Individual --blog_id 1,2

## Example - Executing from Cron

Execute rebuild all archives once a day(at 2:00 am).

    0 2 * * * cd /path/to/mt; perl ./tools/rebuild-archives

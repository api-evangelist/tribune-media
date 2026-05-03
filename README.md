# Tribune Media

Tribune Media was a diversified media and entertainment company with broadcasting, digital, and content businesses. Through Tribune Media Services (TMS), it provided comprehensive entertainment data APIs including TV programming, movie showtimes, celebrity information, and sports data. Tribune Media was acquired by Nexstar Media Group in 2019. The TMS OnConnect APIs are now operated by Gracenote (a Nielsen company), providing metadata for TV shows, movies, celebrities, and televised sports to consumer electronics manufacturers, cable operators, entertainment platforms, and application developers.

**URL:** [View APIs.yml](https://raw.githubusercontent.com/api-evangelist/tribune-media/refs/heads/main/apis.yml)

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### TMS OnConnect API

The Tribune Media Services (TMS) OnConnect API provides comprehensive entertainment metadata for TV programming, movies, celebrities, and sports. It delivers electronic programming guide (EPG) data, movie showtimes, celebrity information, and televised sports schedules.

**Human URL:** [https://developer.tmsapi.com/](https://developer.tmsapi.com/)

#### Tags

- Entertainment, Television, Movies, Sports, Celebrity, Programming Guide, Metadata

#### Properties

- [Documentation](https://developer.tmsapi.com/docs)
- [Getting Started](https://developer.tmsapi.com/Getting_Started)
- [Terms of Service](https://developer.tmsapi.com/page/API_Terms_of_Use)
- [FAQ](https://developer.tmsapi.com/page/Frequently_Asked_Questions)
- [OpenAPI](openapi/tms-onconnect-openapi.yml)

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [TMS OnConnect API](openapi/tms-onconnect-openapi.yml) | Full OnConnect API covering lineups, programs, movies, sports, and celebrities |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [TMS OnConnect Rules](rules/tms-onconnect-rules.yml) | Spectral ruleset enforcing TMS API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/tms-onconnect.yaml](capabilities/shared/tms-onconnect.yaml) | Per-API consumed definition for TMS OnConnect API |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [capabilities/entertainment-discovery.yaml](capabilities/entertainment-discovery.yaml) | Unified entertainment discovery: TV grids, movie showtimes, celebrity appearances, sports events (13 tools) |

## JSON Schema

| Schema | Description |
|---|---|
| [json-schema/tms-program-schema.json](json-schema/tms-program-schema.json) | JSON Schema for TMS program entities |
| [json-schema/tms-airing-schema.json](json-schema/tms-airing-schema.json) | JSON Schema for TMS broadcast airing entities |

## JSON Structure

| Structure | Description |
|---|---|
| [json-structure/tms-program-structure.json](json-structure/tms-program-structure.json) | Structure documentation for TMS programs |
| [json-structure/tms-airing-structure.json](json-structure/tms-airing-structure.json) | Structure documentation for TMS airings |

## JSON-LD Context

| Context | Description |
|---|---|
| [json-ld/tribune-media-context.jsonld](json-ld/tribune-media-context.jsonld) | JSON-LD context mapping TMS vocabulary to schema.org |

## Examples

| Example | Description |
|---|---|
| [examples/tms-onconnect-get-lineups-example.json](examples/tms-onconnect-get-lineups-example.json) | Get TV lineups for a postal code |
| [examples/tms-onconnect-get-lineup-grid-example.json](examples/tms-onconnect-get-lineup-grid-example.json) | Get TV programming grid schedule |
| [examples/tms-onconnect-get-movie-showings-example.json](examples/tms-onconnect-get-movie-showings-example.json) | Get movies in local theatres |
| [examples/tms-onconnect-search-programs-example.json](examples/tms-onconnect-search-programs-example.json) | Search for TV programs |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/tribune-media-vocabulary.yml](vocabulary/tribune-media-vocabulary.yml) | Domain vocabulary for TMS entertainment data |

## Common Links

- **Website:** [https://www.tribunemedia.com/](https://www.tribunemedia.com/)
- **Developer Portal:** [https://developer.tmsapi.com/](https://developer.tmsapi.com/)
- **Documentation:** [https://developer.tmsapi.com/docs](https://developer.tmsapi.com/docs)
- **Getting Started:** [https://developer.tmsapi.com/Getting_Started](https://developer.tmsapi.com/Getting_Started)
- **Terms of Service:** [https://developer.tmsapi.com/page/API_Terms_of_Use](https://developer.tmsapi.com/page/API_Terms_of_Use)
- **Sign Up:** [https://developer.tmsapi.com/member/register](https://developer.tmsapi.com/member/register)

## Maintainers

- **Kin Lane** - kin@apievangelist.com

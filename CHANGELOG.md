# Changelog

All notable changes to this project will be documented in this file.

# [2.5.0](https://github.com/sapphiredev/framework/compare/v2.4.1...v2.5.0) - (2022-05-15)

## 🚀 Features

-   Update to discord.js v13.7.0 (#435) ([a2ea376](https://github.com/sapphiredev/framework/commit/a2ea376f18ddc52b709ad5d6ceb748464b29a63e))

### [2.4.1](https://github.com/sapphiredev/framework/compare/v2.4.0...v2.4.1) (2022-02-18)

### Bug Fixes

-   explicitly bump sapphire dependencies to their latest versions ([df3a3d1](https://github.com/sapphiredev/framework/commit/df3a3d1dc58fc85312ea8db33944a049c88037a7))

## [2.4.0](https://github.com/sapphiredev/framework/compare/v2.3.0...v2.4.0) (2022-02-05)

### Features

-   **commands:** more types for detailed description ([#372](https://github.com/sapphiredev/framework/issues/372)) ([5085644](https://github.com/sapphiredev/framework/commit/5085644fa4037c92a1f435e13a6322b1530a3af5))

### Bug Fixes

-   bump dependencies to their latest versions ([3b35c91](https://github.com/sapphiredev/framework/commit/3b35c915648ff0fad6dd2eb569e5fe360a655726))
-   **message-parser:** do not run commands when the bot has been timed out ([#373](https://github.com/sapphiredev/framework/issues/373)) ([760227d](https://github.com/sapphiredev/framework/commit/760227d8d23a846bccc5615e4ae9fef832c1abb7))

## [2.3.0](https://github.com/sapphiredev/framework/compare/v2.2.2...v2.3.0) (2022-01-08)

### Features

-   allow mention prefix to be disabled ([#350](https://github.com/sapphiredev/framework/issues/350)) ([26ef1dd](https://github.com/sapphiredev/framework/commit/26ef1ddb7b94e32935ec8dcc5beeeb29f1e84207))
-   **arguments:** enum argument ([#354](https://github.com/sapphiredev/framework/issues/354)) ([9a0626c](https://github.com/sapphiredev/framework/commit/9a0626c4b3d89de7bcc47bbbfbefb66ff1fc8653))

### [2.2.2](https://github.com/sapphiredev/framework/compare/v2.2.1...v2.2.2) (2021-12-26)

### Bug Fixes

-   **deps:** update sapphire dependencies ([#342](https://github.com/sapphiredev/framework/issues/342)) ([b706571](https://github.com/sapphiredev/framework/commit/b7065719f2475cb14330a58af46bfd6ef6d90d2f))
-   fixed module building code on DiscordJS v13.4.0 ([#346](https://github.com/sapphiredev/framework/issues/346)) ([b0d860c](https://github.com/sapphiredev/framework/commit/b0d860c578578dc682125c7727d5209adff6a2af))
-   make `BooleanArgument`/`resolveBoolean`'s contexts immutable ([#338](https://github.com/sapphiredev/framework/issues/338)) ([be130fe](https://github.com/sapphiredev/framework/commit/be130fed3193d7ea915a0731dad7fbbfc1dade5f))

### [2.2.1](https://github.com/sapphiredev/framework/compare/v2.2.0...v2.2.1) (2021-12-06)

### Bug Fixes

-   **command:** TS Only - Fixed type of re-export of `Command.Context` ([422a093](https://github.com/sapphiredev/framework/commit/422a093bd88e2d47630247520ded3ca6bc28729a))
-   **deps:** update sapphire dependencies ([#337](https://github.com/sapphiredev/framework/issues/337)) ([0d06bc0](https://github.com/sapphiredev/framework/commit/0d06bc07eae2bef34b66771182a33646ed0bb7ae))

## [2.2.0](https://github.com/sapphiredev/framework/compare/v2.1.4...v2.2.0) (2021-11-21)

### Features

-   deprecate `ExtendedArgument` ([#321](https://github.com/sapphiredev/framework/issues/321)) ([fd6d095](https://github.com/sapphiredev/framework/commit/fd6d0954786746f6f46b9f280d8a34802dd95e00))
-   expose and use namespaces for options, context, etc ([#330](https://github.com/sapphiredev/framework/issues/330)) ([85e7588](https://github.com/sapphiredev/framework/commit/85e7588313e2472b2268856be79196e1473953da))
-   **preconditions:** export all core preconditions ([#322](https://github.com/sapphiredev/framework/issues/322)) ([5a4898f](https://github.com/sapphiredev/framework/commit/5a4898f6faa464fb27c1473676f2d2da0ccc2f75))

### Bug Fixes

-   **Listener:** fixed compile issues on TS 4.5 ([#329](https://github.com/sapphiredev/framework/issues/329)) ([cb40369](https://github.com/sapphiredev/framework/commit/cb40369fe110506d740b965f16e87e3d1bae04b4))

### [2.1.4](https://github.com/sapphiredev/framework/compare/v2.1.3...v2.1.4) (2021-11-06)

### Bug Fixes

-   **deps:** update dependency @sapphire/discord.js-utilities to v4 ([#317](https://github.com/sapphiredev/framework/issues/317)) ([98cafa6](https://github.com/sapphiredev/framework/commit/98cafa670eecd68cbf93ec3c9871142605b2e304))
-   **docs:** replace command usage of `run` to `messageRun` ([#310](https://github.com/sapphiredev/framework/issues/310)) ([6d40eb6](https://github.com/sapphiredev/framework/commit/6d40eb6e9eaf271213521ef3d3a44920a3f5b018))
-   **SapphireClient:** include `Ready` generic type from parent `Client` ([#312](https://github.com/sapphiredev/framework/issues/312)) ([4d528f5](https://github.com/sapphiredev/framework/commit/4d528f5651531ed9419dad7915376076f687594e))
-   update outdated `Args` path in jsdoc ([#309](https://github.com/sapphiredev/framework/issues/309)) ([cd7f1cc](https://github.com/sapphiredev/framework/commit/cd7f1ccc024c4290ef56900a3da0350a12de8192))

### [2.1.3](https://github.com/sapphiredev/framework/compare/v2.1.2...v2.1.3) (2021-10-17)

### Bug Fixes

-   make `CooldownOptions.delay` optional ([#308](https://github.com/sapphiredev/framework/issues/308)) ([ead3f41](https://github.com/sapphiredev/framework/commit/ead3f41a2f6a7d8f1193694fd39003bcb204e114))

### [2.1.2](https://github.com/sapphiredev/framework/compare/v2.1.1...v2.1.2) (2021-10-17)

### Bug Fixes

-   **Command:** use optional access operator ([#307](https://github.com/sapphiredev/framework/issues/307)) ([b1b7822](https://github.com/sapphiredev/framework/commit/b1b7822505f0dbb83d067ec86919ed3d23931d4d))

### [2.1.1](https://github.com/sapphiredev/framework/compare/v2.1.0...v2.1.1) (2021-10-17)

### Bug Fixes

-   register cooldown correctly ([#304](https://github.com/sapphiredev/framework/issues/304)) ([44bf46e](https://github.com/sapphiredev/framework/commit/44bf46e1adb360ac699d61fe914b062879d65702))

## [2.1.0](https://github.com/sapphiredev/framework/compare/v2.0.0...v2.1.0) (2021-10-17)

### Features

-   **pieces:** add options field to read raw options ([#303](https://github.com/sapphiredev/framework/issues/303)) ([9f45bc9](https://github.com/sapphiredev/framework/commit/9f45bc9e7a2518fc8370d0fd227ac0cb1721f51d))

### Bug Fixes

-   allow more npm versions in engines field ([ccecf4e](https://github.com/sapphiredev/framework/commit/ccecf4e9fdb927b4f6ec23b8e4d790fcf719835a))

## [2.0.0](https://github.com/sapphiredev/framework/compare/v1.0.2...v2.0.0) (2021-10-16)

### ⚠ BREAKING CHANGES

-   For TypeScript users only, if you were previously using `from` or `fromAsync` and you expected the error result to be of type `Error`, it will now be `unknown`. You can reset this back to `Error` by providing it as the second generic type argument.
-   **command:** For TypeScript users please rename your `Command#run` methods to `Command#messageRun`
-   `Awaited` type has been renamed to `Awaitable`
-   Updated `@sapphire/pieces` to `3.0.0`
-   Removed `Command#categories`, use `CommandStore#categories` instead
-   **arguments:** Changed the error message of DateArgument
-   **arguments:** Changed the error message of FloatArgument
-   **arguments:** Changed the error message of NumberArgument
-   **arguments:** Changed the error message of IntegerArgument
-   **arguments:** Changed the error message of all arguments that must be run in a guild
-   **arguments:** Changed the error message of GuildNewsThreadChannelArgument
-   **arguments:** Changed the error message of GuildPrivateThreadChannelArgument
-   **arguments:** Changed the error message of GuildPublicThreadChannelArgument
-   **arguments:** Changed the error message of GuildStageVoiceChannelArgument
-   **arguments:** Changed the error message of GuildTextChannelArgument
-   **arguments:** Changed the error message of GuildThreadChannelArgument
-   **arguments:** Changed the error message of GuildVoiceChannelArgument
-   **arguments:** Changed the error message of GuildMemberArgument
-   **arguments:** Changed the error message of UserArgument
-   **arguments:** Made MessageArgumentContext private
-   **arguments:** Stop exposing the channel property in context of the ChannelArgument error
-   **arguments:** Stop exposing the channel property in context of the GuildCategoryChannelArgument error
-   **arguments:** Stop exposing the channel property in context of the GuildNewsChannelArgument error
-   **arguments:** Stop exposing the channel property in context of the GuildPrivateThreadArgument error
-   **arguments:** Stop exposing the channel property in context of the GuildStageVoiceChannelArgument error
-   **arguments:** Stop exposing the channel property in context of the GuildTextChannelArgument error
-   **arguments:** Stop exposing the channel property in context of the GuildThreadChannelArgument error
-   **arguments:** Stop exposing the channel property in context of the GuildVoiceChannelArgument error
-   **arguments:** Rename Identifiers.ArgumentBoolean to Identifiers.ArgumentBooleanError
-   **arguments:** Rename Identifiers.ArgumentCategoryChannel to Identifiers.ArgumentGuildCategoryChannelError
-   **arguments:** Rename Identifiers.ArgumentChannel to Identifiers.ArgumentChannelError
-   **arguments:** Rename Identifiers.ArgumentDate to Identifiers.ArgumentDateError
-   **arguments:** Rename Identifiers.ArgumentDateTooSmall to Identifiers.ArgumentDateTooEarly
-   **arguments:** Rename Identifiers.ArgumentDateTooBig to Identifiers.ArgumentDateTooFar
-   **arguments:** Rename Identifiers.ArgumentDMChannel to Identifiers.ArgumentDMChannelError
-   **arguments:** Rename Identifiers.ArgumentFloat to Identifiers.ArgumentFloatError
-   **arguments:** Rename Identifiers.ArgumentFloatTooBig to Identifiers.ArgumentFloatTooLarge
-   **arguments:** Rename Identifiers.ArgumentGuildChannel to Identifiers.ArgumentGuildChannelError
-   **arguments:** Rename Identifiers.ArgumentGuildChannelMissingGuild to Identifiers.ArgumentGuildChannelMissingGuildError
-   **arguments:** Rename Identifiers.ArgumentHyperlink to Identifiers.ArgumentHyperlinkError
-   **arguments:** Rename Identifiers.ArgumentInteger to Identifiers.ArgumentIntegerError
-   **arguments:** Rename Identifiers.ArgumentIntegerTooBig to Identifiers.ArgumentIntegerTooLarge
-   **arguments:** Rename Identifiers.ArgumentMember to Identifiers.ArgumentMemberError
-   **arguments:** Rename Identifiers.ArgumentMessage to Identifiers.ArgumentMessageError
-   **arguments:** Rename Identifiers.ArgumentNewsChannel to Identifiers.ArgumentGuildNewsChannelError
-   **arguments:** Rename Identifiers.ArgumentNumber to Identifiers.ArgumentNumberError
-   **arguments:** Rename Identifiers.ArgumentNumberTooBig to Identifiers.ArgumentNumberTooLarge
-   **arguments:** Rename Identifiers.ArgumentRole to Identifiers.ArgumentRoleError
-   **arguments:** Rename Identifiers.ArgumentTextChannel to Identifiers.ArgumentGuildTextChannel
-   **arguments:** Rename Identifiers.ArgumentUser to Identifiers.ArgumentUserError
-   **arguments:** Rename Identifiers.ArgumentVoiceChannel to Identifiers.ArgumentGuildVoiceChannel
-   `Identifiers.PreconditionPermissions` has been renamed to `Identifiers.PreconditionClientPermissions`
-   UserError identifier `preconditionPermissions` has been renamed to `preconditionClientPermissions`
-   `Permissions` precondition has been renamed to `ClientPermissions`
-   `PermissionsPrecondition` class has been renamed to `ClientPermissionsPrecondition`
-   **listener:** Listeners will now be automatically unloaded if no emitter is found
-   Changed `guildChannel` argument to return `GuildChannel | ThreadChannel`.
-   Changed `SapphireClient.id`'s type to `Snowflake | null`.
-   Changed `SapphireClientOptions.id`'s type to `Snowflake | null`.
-   Removed `Events.GuildMemberSpeaking`.
-   Removed `StoreRegistry`, it is now re-exported from `@sapphire/pieces`.
-   Renamed `ArgType.categoryChannel` to `guildCategoryChannel`.
-   Renamed `ArgType.newsChannel` to `guildNewsChannel`.
-   Renamed `ArgType.textChannel` to `guildTextChannel`.
-   Renamed `ArgType.voiceChannel` to `guildVoiceChannel`.
-   Renamed `CommandPreConditions.NewsOnly` to `GuildNewsOnly`.
-   Renamed `CommandPreConditions.TextOnly` to `GuildTextOnly`.
-   Renamed `Identifiers.PreconditionNewsOnly` to `PreconditionGuildNewsOnly`.
-   Renamed `Identifiers.PreconditionTextOnly` to `PreconditionGuildTextOnly`.
-   Renamed `Preconditions.NewsOnly` to `GuildNewsOnly`.
-   Renamed `Preconditions.TextOnly` to `GuildTextOnly`.
-   Renamed the possible values for `CommandOptionsRunType`.
-   Updated `CooldownContext.delay` to not be optional.
-   Updated `discord.js` requirement to v13.
-   Changed `Command#preconditions` to `PreconditionContainerArray`.
-   Removed `Command#resolveConstructorPreConditions`.
-   Renamed `CommandOptions.cooldownBucket` to `cooldownLimit`.
-   Renamed `CommandOptions.cooldownDuration` to `cooldownDelay`.
-   Renamed `BucketType` to `BucketScope`.
-   Changed `PreconditionSingleResolvableDetails` to take a type parameter.
-   Changed `PreconditionSingleResolvable` to use `Preconditions`'s type.
-   Renamed `CooldownContext.bucketType` to `scope`.
-   Renamed `Event` to `Listener`
-   Renamed `EventStore` to `ListenerStore`
-   Changed events directory from `events` to `listeners`
-   Renamed `SapphireClientOptions.loadDefaultErrorEvents` to `loadDefaultErrorListeners`
-   Renamed `StoreRegistryEntries.events` to `StoreRegistryEntries.listeners`
-   Refactored `Events` enum to be an object, so we can use discord.js's constants
-   Renamed `Events.EventError` to `Events.ListenerError`
-   Renamed `EventErrorPayload` to `ListenerErrorPayload`
-   Renamed `Events.Ready` to `Events.ClientReady`
-   Renamed `Events.Message` to `Events.MessageCreate`
-   Flattened `CommandOptions.strategyOptions` into `CommandOptions`
-   Changed `CommandOptions.preconditions` to always require an array
-   Updated `@sapphire/pieces` to 2.0.0
-   Renamed `PieceContextExtras` to `Container`, usage and augmentation is the same.
-   Removed `Store.injectedContext`, use globally exported `container`
    variable instead.
-   Renamed `Store#context` to `Store#container`.
-   Renamed `Piece#context` to `Piece#container`.

### Features

-   add `Result#from` and `Result#fromAsync` ([#267](https://github.com/sapphiredev/framework/issues/267)) ([300f2ed](https://github.com/sapphiredev/framework/commit/300f2ed7a279b39584af4b38062a9096b31f32bb))
-   Add `typing` property to fire `TextChannel.sendTyping()` when a command is accepted ([#258](https://github.com/sapphiredev/framework/issues/258)) ([71c1883](https://github.com/sapphiredev/framework/commit/71c1883060a03595e9ae5afa44038f84e404c40f))
-   add managed role mention prefix support ([#289](https://github.com/sapphiredev/framework/issues/289)) ([7846d6c](https://github.com/sapphiredev/framework/commit/7846d6c19bff904fd4b915ccebf5392b31cffbad))
-   add partial dm channel argument ([#288](https://github.com/sapphiredev/framework/issues/288)) ([c8c74de](https://github.com/sapphiredev/framework/commit/c8c74de3d6484be4354f6ec77477c29617fdd7ab))
-   add UserPermissions precondition ([#252](https://github.com/sapphiredev/framework/issues/252)) ([2bb2e12](https://github.com/sapphiredev/framework/commit/2bb2e1228c299f8c085b276b3fbd2790c6c7bae5))
-   added auto-preconditions ([#199](https://github.com/sapphiredev/framework/issues/199)) ([7e79e15](https://github.com/sapphiredev/framework/commit/7e79e156a312fead281db4756f1e838a8fab41c9))
-   **arguments:** extract logic to resolvers ([#237](https://github.com/sapphiredev/framework/issues/237)) ([32d591b](https://github.com/sapphiredev/framework/commit/32d591b6da02215303305ff8d58a7e6ef67333d1))
-   **client:** added option to set a default cooldown for all commands ([#294](https://github.com/sapphiredev/framework/issues/294)) ([7734d59](https://github.com/sapphiredev/framework/commit/7734d591374be3256556bd53e5240d1ad4250e7f))
-   **command:** add `command#messageRun` method and deprecation warning for `command#run` ([#299](https://github.com/sapphiredev/framework/issues/299)) ([750c25c](https://github.com/sapphiredev/framework/commit/750c25c9526cc9999d1fadaa10719470d36d0e1a))
-   **command:** add CommandOptionsRunTypeEnum ([#254](https://github.com/sapphiredev/framework/issues/254)) ([2d21b03](https://github.com/sapphiredev/framework/commit/2d21b0389ef833c90285119552f71e8c64582fc6))
-   **commands:** add category getters ([#244](https://github.com/sapphiredev/framework/issues/244)) ([d438ac0](https://github.com/sapphiredev/framework/commit/d438ac007032ed369a090ec50097fe86a437cd14))
-   **cooldown:** add `cooldownFilteredUsers` to exempt users from the cooldown precondition ([#249](https://github.com/sapphiredev/framework/issues/249)) ([8261770](https://github.com/sapphiredev/framework/commit/82617709e81141283798a70d02bedcdfeed4dbf0))
-   **ILogger:** add #has method, auto-register Store#logger ([#221](https://github.com/sapphiredev/framework/issues/221)) ([85bfacb](https://github.com/sapphiredev/framework/commit/85bfacb83aca0b27c9bb60272ae4db5c58ed06a9))
-   **member argument:** slice off Discord discriminators before performing a query search ([#301](https://github.com/sapphiredev/framework/issues/301)) ([f6261ae](https://github.com/sapphiredev/framework/commit/f6261aeaf4c3f000a02e91d35e6f44a1248fb10c))
-   NonePrefixedMessage event ([#202](https://github.com/sapphiredev/framework/issues/202)) ([a410bbf](https://github.com/sapphiredev/framework/commit/a410bbf7ea964758990ef5d28613ae438f2de2f4))
-   **resolver:** make resolveChannel parse mentions ([#253](https://github.com/sapphiredev/framework/issues/253)) ([506576e](https://github.com/sapphiredev/framework/commit/506576ebda7c9dd4ace42bc140e2b08754d57826))
-   **resolver:** make resolveMessage parse channelId-messageId ([#292](https://github.com/sapphiredev/framework/issues/292)) ([5e915d0](https://github.com/sapphiredev/framework/commit/5e915d082deb52b1805c80a0aedf346fe3a92c42))
-   specify missing breaking changes ([9097cf5](https://github.com/sapphiredev/framework/commit/9097cf57421863733969345b4fb13e0c491340d1))
-   stricter types for preconditions ([#226](https://github.com/sapphiredev/framework/issues/226)) ([4a3c76a](https://github.com/sapphiredev/framework/commit/4a3c76a60128e8568150c4fb8b2f1c4e5efd5d5e))
-   update @sapphire/pieces to add `ts-node` support ([7a1c5c6](https://github.com/sapphiredev/framework/commit/7a1c5c693004f7eed53aa6e0d8abd104dcf09263))
-   update to DiscordJS v13.2.0 ([#295](https://github.com/sapphiredev/framework/issues/295)) ([51808a5](https://github.com/sapphiredev/framework/commit/51808a5bde087a45daa3caa084c118e7e7f02ef4))
-   updated for `pieces` v3 ([#260](https://github.com/sapphiredev/framework/issues/260)) ([db6febd](https://github.com/sapphiredev/framework/commit/db6febd56afeaeff1f23afce2a269beecb316804))

### Bug Fixes

-   change `Awaited` to `Awaitable` ([189c01f](https://github.com/sapphiredev/framework/commit/189c01fc5bafbc0dcf6d5bed6be29bf02b408fac))
-   **docs:** it was always `info` ([3ce4d71](https://github.com/sapphiredev/framework/commit/3ce4d7165163fcf8efd3d6f01ab49e857b453e14))
-   **docs:** update-tsdoc-for-vscode-may-2021 ([#213](https://github.com/sapphiredev/framework/issues/213)) ([857eaba](https://github.com/sapphiredev/framework/commit/857eaba385d371edffe157613a32c4ead2a4724c))
-   explicitly type `version` as `string` ([a8c9b39](https://github.com/sapphiredev/framework/commit/a8c9b3921a6404fc0f1483d444930a212578aea3))
-   export `CooldownContext` and `MessageArgumentContext` ([54ba95a](https://github.com/sapphiredev/framework/commit/54ba95abdb72cb44d45353512a0f942d54dc1c42))
-   fixed ESM bundle ([7ca08b2](https://github.com/sapphiredev/framework/commit/7ca08b23426e120a845499d1c04d956ba0d460c5))
-   fixed oversight in passing preconditions ([#239](https://github.com/sapphiredev/framework/issues/239)) ([380a4ef](https://github.com/sapphiredev/framework/commit/380a4ef3b350e25d68138dbb89a7f7dfb6b8495e))
-   **index:** re-export `StoreRegistryEntries` from `@sapphire/pieces` ([#243](https://github.com/sapphiredev/framework/issues/243)) ([aa78ba9](https://github.com/sapphiredev/framework/commit/aa78ba9ec72a92d3362d7c22929790e0209e9270))
-   **listener:** add and remove maximum listeners ([#230](https://github.com/sapphiredev/framework/issues/230)) ([53681ad](https://github.com/sapphiredev/framework/commit/53681ad9e5ffb7059072bfb754ccd241ca8d6611))
-   make from/fromAsync return `unknown` to match TypeScript ([#300](https://github.com/sapphiredev/framework/issues/300)) ([a83f0c9](https://github.com/sapphiredev/framework/commit/a83f0c93da5e0bfeb7cb1ee682427891924bc44a))
-   **NonePrefixedMessage:** rename to NonPrefixedMessage ([#205](https://github.com/sapphiredev/framework/issues/205)) ([ad8adbc](https://github.com/sapphiredev/framework/commit/ad8adbced272cf8fd1db043a1ea60f7e19067551))
-   **preconditions:** fixed TextOnly and NewsOnly ([#222](https://github.com/sapphiredev/framework/issues/222)) ([8cf1c2b](https://github.com/sapphiredev/framework/commit/8cf1c2b60da7f9f421500d0ef9f035be08284f90))
-   **preconditions:** fixed UserPermissions precondition ([1848f53](https://github.com/sapphiredev/framework/commit/1848f53004d6fedda6b1b559385f77e35f616d9d))
-   **preconditions:** properly check for `null` in ClientPermissions and UserPermissions ([#262](https://github.com/sapphiredev/framework/issues/262)) ([852ee87](https://github.com/sapphiredev/framework/commit/852ee878d04debb08e8f8b5985434d479167a31a))
-   remove peer deps, update dev deps, update READMEs ([#210](https://github.com/sapphiredev/framework/issues/210)) ([7cb9e3d](https://github.com/sapphiredev/framework/commit/7cb9e3da7f70d013fc0b97c911576e4df90b321e))
-   **types:** use the correct channel parent type ([#232](https://github.com/sapphiredev/framework/issues/232)) ([8307313](https://github.com/sapphiredev/framework/commit/8307313835a038e8e6c4a7e7a673ca12ceaf70d1))
-   update `@sapphire/pieces` to v2.0.0 ([#198](https://github.com/sapphiredev/framework/issues/198)) ([5c95c32](https://github.com/sapphiredev/framework/commit/5c95c32ff52ef18d2544de03484fbfd00f0d5016))

-   flatten command strategy options ([#220](https://github.com/sapphiredev/framework/issues/220)) ([fdc4aa4](https://github.com/sapphiredev/framework/commit/fdc4aa40b873e60ea9bc14a6cafd6a8513ae1ac8))
-   rename `Event` to `Listener` ([#218](https://github.com/sapphiredev/framework/issues/218)) ([e7ce612](https://github.com/sapphiredev/framework/commit/e7ce612b62bb825dd471acebb6e56cd4bbc866fc))
-   specify missing breaking changes ([b9c36de](https://github.com/sapphiredev/framework/commit/b9c36de77fc8dcf3148ad44ce917368874335e9e))
-   switch to `sapphire/*[@v2](https://github.com/v2)` and `discord.js@dev` ([#227](https://github.com/sapphiredev/framework/issues/227)) ([cbf5d4e](https://github.com/sapphiredev/framework/commit/cbf5d4e3e917c08413e300d82df3e28168d7c18d))

### [1.0.2](https://github.com/sapphiredev/framework/compare/v1.0.1...v1.0.2) (2021-05-02)

### Bug Fixes

-   drop the `www.` from the SapphireJS URL ([e9ed4e8](https://github.com/sapphiredev/framework/commit/e9ed4e830195645e42bc57b0c02e139a82ac415f))
-   update all the SapphireJS URLs from `.com` to `.dev` ([4d0c8ea](https://github.com/sapphiredev/framework/commit/4d0c8ea364015970e13b93a9aa3a4142ed911635))

### [1.0.1](https://github.com/sapphiredev/framework/compare/v1.0.0...v1.0.1) (2021-04-21)

### Bug Fixes

-   **dependencies:** update in semver scope dependencies ([ca9a2c1](https://github.com/sapphiredev/rk/commit/ca9a2c1af7b699be9cfe7e1276d874846b6150d7))
-   change all Sapphire URLs from "project"->"community" & use our domain where applicable 👨‍🌾🚜 ([#192](https://github.com/sapphiredev/rk/issues/192)) ([650260e](https://github.com/sapphi/sapphiredev/it/650260e778181d3dbb2c4a880db7535eb4d92650))

## [1.0.0](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.11...v1.0.0) (2021-03-16)

### Features

-   export sapphire package version ([#181](https://github.com/sapphiredev/rk/issues/181)) ([6df4be0](https://github.com/sapphi/sapphiredev/it/6df4be0b58e66cb7f268d10dbe64287e9ec783b2))

### Bug Fixes

-   make `conditions` public ([#178](https://github.com/sapphiredev/rk/issues/178)) ([d1d4027](https://github.com/sapphi/sapphiredev/it/d1d40271040759aa63f112eaa4a02b791514be83))
-   update dependencies ([59ddbd6](https://github.com/sapphiredev/rk/commit/59ddbd663745cd49da0e0db3e7bab45190c7cd5a))

## [1.0.0-alpha.11](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.10...v1.0.0-alpha.11) (2021-02-16)

### Features

-   **structures:** add global preconditions ([#176](https://github.com/sapphiredev/rk/issues/176)) ([e8ef41f](https://github.com/sapphi/sapphiredev/it/e8ef41fbbc420ee8cc2283d99554fc16d241fec8))

### Bug Fixes

-   **enabled:** remove last remnant of essentials ([4928823](https://github.com/sapphiredev/rk/commit/4928823751baa8f9e6a6f4e3c4237055f56e1384))

## [1.0.0-alpha.10](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.9...v1.0.0-alpha.10) (2021-02-12)

### ⚠ BREAKING CHANGES

-   **command-accepted:** `Events.CommandRun` third argument changed type to `CommandRunPayload`,
    this is mostly identical to `CommandAcceptedPayload` (and exactly identical to `CommandFinishPayload`)
    and likely won't be a breaking change for your code, however you may need to adjust
    your import when using TypeScript.
-   **command-accepted:** `Events.CommandFinish` third argument changed type to `CommandFinishPayload`,
    this is mostly identical to `CommandAcceptedPayload` (and exactly identical to `CommandRunPayload`)
    and likely won't be a breaking change for your code, however you may need to adjust
    your import when using TypeScript.

### Features

-   **args:** add `name` to context of `Args.unavailableArgument` ([#171](https://github.com/sapphiredev/rk/issues/171)) ([a5bda61](https://github.com/sapphi/sapphiredev/it/a5bda611108fc7e382a62f292a667f0228bf2dfa))
-   **args:** add more data to error context for core arguments ([0cfff79](https://github.com/sapphiredev/rk/commit/0cfff793c8f9c8ede6d954a0dbeaad2e7647cb15))
-   **args:** pass more context to args errors ([#174](https://github.com/sapphiredev/rk/issues/174)) ([007eaed](https://github.com/sapphi/sapphiredev/it/007eaed76e827bde8d75c9db368620e55b4b017e))
-   **argumenterror:** add type default of `unknown` ([55be30a](https://github.com/sapphiredev/rk/commit/55be30ae4d279067f8dbedab12ba9c034d197cbc))
-   **command-accepted:** add received args to event payloads ([#173](https://github.com/sapphiredev/rk/issues/173)) ([fa60b13](https://github.com/sapphi/sapphiredev/it/fa60b13247b71927a26e4738596155b6c041afcb))
-   **message-parser:** add `caseInsensitivePrefixes` client option ([#170](https://github.com/sapphiredev/rk/issues/170)) ([61f9c41](https://github.com/sapphi/sapphiredev/it/61f9c41d53f641a92a1f344cba96a2d5ae589d43))

## [1.0.0-alpha.9](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.8...v1.0.0-alpha.9) (2021-02-07)

### ⚠ BREAKING CHANGES

-   **preconditions:** Changed PreconditionContext.command to external

### Features

-   **events:** added UnknownCommandPayload.commandName ([#166](https://github.com/sapphiredev/rk/issues/166)) ([3dbcffd](https://github.com/sapphi/sapphiredev/it/3dbcffd86b7ab6d4718b6ea040efa094686f9cdd))

-   **preconditions:** make IPreconditionContainer#run's context optional ([#167](https://github.com/sapphiredev/rk/issues/167)) ([57ad8d2](https://github.com/sapphi/sapphiredev/it/57ad8d2f6f080ad0a9f9336548522ee539aec84e))

## [1.0.0-alpha.8](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.7...v1.0.0-alpha.8) (2021-02-07)

### ⚠ BREAKING CHANGES

-   **events:** Changed `Events.UnknownCommandName` event arguments to `UnknownCommandNamePayload`.
-   **events:** Changed `Events.UnknownCommand` event arguments to `UnknownCommandPayload`.

Co-authored-by: Jeroen Claassens <support@favware.tech>

-   **events:** CoreMessageParser is not longer a message event listener

### Features

-   **events:** create Events.PreMessageParsed ([#164](https://github.com/sapphiredev/rk/issues/164)) ([0311838](https://github.com/sapphi/sapphiredev/it/0311838d59d7071a37ea932a094dbab0c26e84c1))

-   **events:** remove UnknownCommandName, changed UnknownCommand ([#165](https://github.com/sapphiredev/rk/issues/165)) ([c3273d1](https://github.com/sapphi/sapphiredev/it/c3273d100259c3905c5d3955be4a3b1d5aec24ef))

## [1.0.0-alpha.7](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.6...v1.0.0-alpha.7) (2021-02-06)

### ⚠ BREAKING CHANGES

-   **errors:** Changed UserError identifier from `'ArgumentBooleanInvalidBoolean'` to `Identifiers.ArgumentBoolean`.
-   **errors:** Changed UserError identifier from `'ArgumentCategoryChannelInvalidChannel'` to `Identifiers.ArgumentCategoryChannel`.
-   **errors:** Changed UserError identifier from `'ArgumentChannelMissingChannel'` to `Identifiers.ArgumentChannel`.
-   **errors:** Changed UserError identifier from `'ArgumentDateInvalidNumber'` to `Identifiers.ArgumentDate`.
-   **errors:** Changed UserError identifier from `'ArgumentDateTooSmall'` to `Identifiers.ArgumentDateTooSmall`.
-   **errors:** Changed UserError identifier from `'ArgumentDateTooBig'` to `Identifiers.ArgumentDateTooBig`.
-   **errors:** Changed UserError identifier from `'ArgumentDMChannelInvalidChannel'` to `Identifiers.ArgumentDMChannel`.
-   **errors:** Changed UserError identifier from `'ArgumentFloatInvalidFloat'` to `Identifiers.ArgumentFloat`.
-   **errors:** Changed UserError identifier from `'ArgumentFloatTooSmall'` to `Identifiers.ArgumentFloatTooSmall`.
-   **errors:** Changed UserError identifier from `'ArgumentFloatTooBig'` to `Identifiers.ArgumentFloatTooBig`.
-   **errors:** Changed UserError identifier from `'ArgumentGuildChannelMissingGuild'` to `Identifiers.ArgumentGuildChannelMissingGuild`.
-   **errors:** Changed UserError identifier from `'ArgumentGuildChannelUnknownChannel'` to `Identifiers.ArgumentGuildChannel`.
-   **errors:** Changed UserError identifier from `'ArgumentHyperlinkInvalidURL'` to `Identifiers.ArgumentHyperlink`.
-   **errors:** Changed UserError identifier from `'ArgumentIntegerInvalidNumber'` to `Identifiers.ArgumentInteger`.
-   **errors:** Changed UserError identifier from `'ArgumentIntegerTooSmall'` to `Identifiers.ArgumentIntegerTooSmall`.
-   **errors:** Changed UserError identifier from `'ArgumentIntegerTooBig'` to `Identifiers.ArgumentIntegerTooBig`.
-   **errors:** Changed UserError identifier from `'ArgumentMemberMissingGuild'` to `Identifiers.ArgumentMemberMissingGuild`.
-   **errors:** Changed UserError identifier from `'ArgumentMemberUnknownMember'` to `Identifiers.ArgumentMember`.
-   **errors:** Changed UserError identifier from `'ArgumentMessageUnknownMessage'` to `Identifiers.Message`.
-   **errors:** Changed UserError identifier from `'ArgumentNewsChannelInvalidChannel'` to `Identifiers.NewsChannel`.
-   **errors:** Changed UserError identifier from `'ArgumentNumberInvalidNumber'` to `Identifiers.Number`.
-   **errors:** Changed UserError identifier from `'ArgumentNumberTooSmall'` to `Identifiers.ArgumentNumberTooSmall`.
-   **errors:** Changed UserError identifier from `'ArgumentNumberTooBig'` to `Identifiers.ArgumentNumberTooBig`.
-   **errors:** Changed UserError identifier from `'ArgumentRoleMissingGuild'` to `Identifiers.ArgumentRoleMissingGuild`.
-   **errors:** Changed UserError identifier from `'ArgumentRoleUnknownRole'` to `Identifiers.Role`.
-   **errors:** Changed UserError identifier from `'ArgumentStringTooShort'` to `Identifiers.ArgumentStringTooShort`.
-   **errors:** Changed UserError identifier from `'ArgumentStringTooLong'` to `Identifiers.ArgumentStringTooLong`.
-   **errors:** Changed UserError identifier from `'ArgumentTextChannelInvalidChannel'` to `Identifiers.TextChannel`.
-   **errors:** Changed UserError identifier from `'ArgumentUserUnknownUser'` to `Identifiers.User`.
-   **errors:** Changed UserError identifier from `'ArgumentVoiceChannelInvalidChannel'` to `Identifiers.VoiceChannel`.
-   **errors:** Changed UserError identifier from `'CommandDisabled'` to `Identifiers.CommandDisabled`.
-   **errors:** Changed UserError identifier from `'UnavailableArgument'` to `Identifiers.ArgsUnavailable`.
-   **errors:** Changed UserError identifier from `'MissingArguments'` to `Identifiers.ArgsMissing`.
-   **errors:** Changed UserError identifier from `'Cooldown'` to `Identifiers.PreconditionCooldown`.
-   **errors:** Changed UserError identifier from `'DMOnly'` to `Identifiers.PreconditionDMOnly`.
-   **errors:** Changed UserError identifier from `'GuildOnly'` to `Identifiers.PreconditionGuildOnly`.
-   **errors:** Changed UserError identifier from `'NSFW'` to `Identifiers.PreconditionNSFW`.
-   **errors:** Changed UserError identifier from `'Permissions'` to `Identifiers.PreconditionPermissions`.
-   **preconditions:** Added `PreconditionContext` as third parameter to `IPreconditionContainer#run`.
-   **preconditions:** Changed `PermissionsPrecondition#context` from `PreconditionContext` to `Record<PropertyKey, unknown>`.
-   **preconditions:** Changed `PreconditionContainerSingle#context` from `PreconditionContext` to `Record<PropertyKey, unknown>`.
-   **preconditions:** Changed `PreconditionSingleResolvableDetails#context` from `PreconditionContext` to `Record<PropertyKey, unknown>`.
-   **preconditions:** Added `PreconditionContext` as third parameter to `IPreconditionCondition#run`.
-   **args:** changed `Args.err` to return `Err<ArgumentError<T>>` instead of `ArgumentError<T>`

### Features

-   **args:** add Args#ok, refactored Args#error to return Err<ArgumentError<T>> ([#159](https://github.com/sapphiredev/rk/issues/159)) ([65316a6](https://github.com/sapphi/sapphiredev/it/65316a6f13533b90b0ba84ff214ebf8bb54cc5ee))
-   **args:** change visibility of parser from private to protected ([#160](https://github.com/sapphiredev/rk/issues/160)) ([3ad6f85](https://github.com/sapphi/sapphiredev/it/3ad6f85db92287c0c073dcbc21df13d52c629abb))
-   **command:** add CommandContext#commandPrefix ([#157](https://github.com/sapphiredev/rk/issues/157)) ([c8c7417](https://github.com/sapphi/sapphiredev/it/c8c741768e78a5f3c75282cc8461368bd9609016))
-   **command-events:** pass more context ([#162](https://github.com/sapphiredev/rk/issues/162)) ([11a6274](https://github.com/sapphi/sapphiredev/it/11a6274613536fcc7fa2bcbb936b6332740978a4))
-   **errors:** expose all identifiers in an enum ([#161](https://github.com/sapphiredev/rk/issues/161)) ([3371f35](https://github.com/sapphi/sapphiredev/it/3371f35c2ad9fabdacca5b1ae614e5a5c9530dbc))
-   **preconditions:** add context to Container and Condition ([#158](https://github.com/sapphiredev/rk/issues/158)) ([de6bc03](https://github.com/sapphi/sapphiredev/it/de6bc035f737ddc269a1b7e44ad34c175cfa35dd))

## [1.0.0-alpha.6](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.5...v1.0.0-alpha.6) (2021-02-04)

### Bug Fixes

-   **preconditions:** make options optional ([#155](https://github.com/sapphiredev/rk/issues/155)) ([ecc5323](https://github.com/sapphi/sapphiredev/it/ecc5323dc0213524c0bf21a47b52aac3357528ac))

## [1.0.0-alpha.5](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.4...v1.0.0-alpha.5) (2021-02-02)

### ⚠ BREAKING CHANGES

-   **client:** `client.arguments` is now `client.stores.get('arguments')`
-   **client:** `client.commands` is now `client.stores.get('commands')`
-   **client:** `client.events` is now `client.stores.get('events')`
-   **client:** `client.preconditions` is now `client.stores.get('preconditions')`
-   **client:** `client.registerUserDirectories` is now `client.stores.registerUserDirectories`
-   **client:** `client.deregisterStore` is now `client.stores.deregister`
-   **client:** `client.registerStore` is now `client.stores.register`
-   **command parser:** The events `prefixedMessage`, `unknownCommandName`, and `unknownCommand` 3rd
    parameter now have the type `string | RegExp`
-   **command parser:** `CommandContext.prefix` now has the type `string | RegExp`
-   The `UserError`, `PreconditionError`, `ArgumentError` classes,
    and the `ok`, `err` functions now take a single parameter which is an object
    of properties, rather than multiple parameters.

### Features

-   **args:** add Args#commandContext ([#154](https://github.com/sapphiredev/rk/issues/154)) ([63c195b](https://github.com/sapphi/sapphiredev/it/63c195bde51cb069ef141f4da5990717e2c092da))
-   **client:** change stores from a Set to a Map ([#129](https://github.com/sapphiredev/rk/issues/129)) ([01f7161](https://github.com/sapphi/sapphiredev/it/01f716153e8d2e1865cc2402736c6aadb1247c60))
-   **command:** add generateDashLessAliases ([#146](https://github.com/sapphiredev/rk/issues/146)) ([e94649c](https://github.com/sapphi/sapphiredev/it/e94649c2c7ae2840a7a08be59fa1daf9227bbfc0))
-   **command parser:** add regexPrefix client option ([#145](https://github.com/sapphiredev/rk/issues/145)) ([86e6b79](https://github.com/sapphi/sapphiredev/it/86e6b7960956674c5f0140e6c78bd75e899d559c))
-   **preconditions:** make Permission errors less vague ([#151](https://github.com/sapphiredev/rk/issues/151)) ([c6b04e1](https://github.com/sapphi/sapphiredev/it/c6b04e16163b580021e1986b541cb9d4247865ab))
-   make errors take objects instead of many params ([#144](https://github.com/sapphiredev/rk/issues/144)) ([f638410](https://github.com/sapphi/sapphiredev/it/f6384101a1a07620df2ad293d138a793a3a724fb))

### Bug Fixes

-   update discord redirect URL ([61edce2](https://github.com/sapphiredev/rk/commit/61edce2040f6d88e9da3bb8a9f5eb10cd0cb60a5))

## [1.0.0-alpha.4](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.3...v1.0.0-alpha.4) (2021-01-28)

### Features

-   **argument:** pass args through context ([#142](https://github.com/sapphiredev/rk/issues/142)) ([cfeef64](https://github.com/sapphi/sapphiredev/it/cfeef6479427353d9e681fb92dc578ed4412aa2a))
-   **arguments:** add CoreCategoryChannel ([#136](https://github.com/sapphiredev/rk/issues/136)) ([4c281a3](https://github.com/sapphi/sapphiredev/it/4c281a33c2852bee3daac160ed76f0cc2ab9b0ad))
-   **command:** expose Command#lexer ([#143](https://github.com/sapphiredev/rk/issues/143)) ([4ec1b4d](https://github.com/sapphi/sapphiredev/it/4ec1b4da6c2524b2e4c8b8b2ebb298707a7633c4))
-   add optional default error events ([#141](https://github.com/sapphiredev/rk/issues/141)) ([27fd086](https://github.com/sapphi/sapphiredev/it/27fd086b2900be658a458e93e3ea29b60450fba3))

### Bug Fixes

-   add discord.js utilities for type guards ([cf74431](https://github.com/sapphiredev/rk/commit/cf7443176a7080a8826ad9a15711863bc8d021a1))

## [1.0.0-alpha.3](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.2...v1.0.0-alpha.3) (2021-01-14)

### Features

-   **args:** add Args#nextMaybe and Args#next ([#130](https://github.com/sapphiredev/rk/issues/130)) ([10a6e0b](https://github.com/sapphi/sapphiredev/it/10a6e0b36f72353ea3b25a89fa16fb001711e225))
-   add client#deregisterStore ([#128](https://github.com/sapphiredev/rk/issues/128)) ([dedd6d1](https://github.com/sapphi/sapphiredev/it/dedd6d1149ab58f35e1dede88c67eefacfd070c7))
-   **args:** add Args#finished ([#125](https://github.com/sapphiredev/rk/issues/125)) ([36e0a1f](https://github.com/sapphi/sapphiredev/it/36e0a1f11ae75bb4709f469ac12d18b74d853aac))
-   **arguments:** more descriptive error messages ([#127](https://github.com/sapphiredev/rk/issues/127)) ([04931bc](https://github.com/sapphi/sapphiredev/it/04931bcc3216d68242338c026cd54b10fd53878d))

### Bug Fixes

-   change CoreBoolean error signature ([#126](https://github.com/sapphiredev/rk/issues/126)) ([9ca7456](https://github.com/sapphi/sapphiredev/it/9ca74564fe4fa3ecf9bcac72b30398b11bb6d029))

## [1.0.0-alpha.2](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.1...v1.0.0-alpha.2) (2021-01-03)

### Features

-   **args:** allow peeking arguments ([#121](https://github.com/sapphiredev/rk/issues/121)) ([4786d48](https://github.com/sapphi/sapphiredev/it/4786d48e5ddabf292fca3a09dfc55f685087368a))

### Bug Fixes

-   **index:** export PreconditionError ([#124](https://github.com/sapphiredev/rk/issues/124)) ([5daa3c9](https://github.com/sapphi/sapphiredev/it/5daa3c965960710c7e088e8245e5e1d9875d34eb))

## [1.0.0-alpha.1](https://github.com/sapphiredev/rk/compare/v1.0.0-alpha.0...v1.0.0-alpha.1) (2020-12-28)

### Features

-   new preconditions ([#119](https://github.com/sapphiredev/rk/issues/119)) ([10c7a1b](https://github.com/sapphi/sapphiredev/it/10c7a1b1a83838c89ac6d858cdc3a507ad1ab32a))
-   **arguments:** Add Message argument, use discord-utilities ([#118](https://github.com/sapphiredev/rk/issues/118)) ([c70af0a](https://github.com/sapphi/sapphiredev/it/c70af0ab0fc241691b88da9bc7b8bcc6c97efa28))
-   **logger:** make Logger.levels protected ([5a4b8d6](https://github.com/sapphiredev/rk/commit/5a4b8d6e5c86f7f2c5153730d4565654c54a59c0))

### 1.0.0-alpha.0 (2020-12-22)

### Features

-   re-export public-facing structures from pieces ([#113](https://github.com/sapphiredev/rk/issues/113)) ([648a57d](https://github.com/sapphi/sapphiredev/it/648a57dd1e9b5ca7494a28378c759141613ea1ee))
-   output type declarations to a single .d.ts file ([#112](https://github.com/sapphiredev/rk/issues/112)) ([2652a9b](https://github.com/sapphi/sapphiredev/it/2652a9be2077dee456cdc0241977473e887c5a11))
-   allow case insensitive commands ([#105](https://github.com/sapphiredev/rk/issues/105)) ([a9485ec](https://github.com/sapphi/sapphiredev/it/a9485ec6514c96ac54e700a6a990608915959e79))
-   **arguments:** add CoreBoolean argument ([#96](https://github.com/sapphiredev/rk/issues/96)) ([c4c25c3](https://github.com/sapphi/sapphiredev/it/c4c25c3ac6817ec35004570005b8f120911a68a6))
-   **arguments:** Add extended argument functionality ([#101](https://github.com/sapphiredev/rk/issues/101)) ([8fa9e7b](https://github.com/sapphi/sapphiredev/it/8fa9e7bd794409be14acfd0ac6b1466858ca628d))
-   **arguments:** added more resolvers ([#63](https://github.com/sapphiredev/rk/issues/63)) ([4eb1016](https://github.com/sapphi/sapphiredev/it/4eb1016064f29f2f55c7c6f51cf2e482a521200c))
-   **arguments:** Improve ID/mention checking of members, roles, and users ([#100](https://github.com/sapphiredev/rk/issues/100)) ([008dd44](https://github.com/sapphi/sapphiredev/it/008dd44172c7b93265a7866daeaabd991e59b309))
-   **arguments:** more helpers, added richer errors ([#59](https://github.com/sapphiredev/rk/issues/59)) ([59027d8](https://github.com/sapphi/sapphiredev/it/59027d8955c7c89a4606df037362231621a10ef7))
-   **commands:** add an optional context parameter ([#93](https://github.com/sapphiredev/rk/issues/93)) ([8e1d4f8](https://github.com/sapphi/sapphiredev/it/8e1d4f8ea2534135faeffb131e67d55177cc4bbf))
-   add event types to event pieces ([#27](https://github.com/sapphiredev/rk/issues/27)) ([770101f](https://github.com/sapphi/sapphiredev/it/770101f8284b045e72de49998249509ab0b83d1a))
-   add pregenericsinitialization plugin hook ([#45](https://github.com/sapphiredev/rk/issues/45)) ([972c2d4](https://github.com/sapphi/sapphiredev/it/972c2d46a24ae0c22a82f3fd17a7220f5330d6c5))
-   added a lot more features ([4051121](https://github.com/sapphiredev/rk/commit/40511217dec2bf9f31dd5c05489eb8aca0e273e9))
-   added cooldown precondition ([#76](https://github.com/sapphiredev/rk/issues/76)) ([cfabf52](https://github.com/sapphi/sapphiredev/it/cfabf524a0bcfdec020d9d0e5775b44b6744c866))
-   added events ([524f58c](https://github.com/sapphiredev/rk/commit/524f58cb291580fc812d67011c516d396e4a5ac4))
-   added missing imports ([7688a0a](https://github.com/sapphiredev/rk/commit/7688a0ae5422bdd5f32e9b068ad7636ab443adee))
-   added permissions precondition and utilities ([#64](https://github.com/sapphiredev/rk/issues/64)) ([123a975](https://github.com/sapphi/sapphiredev/it/123a9757e7c39d5c1ed83bf8a739d79b0a1e8118))
-   added Result, finished PreconditionContainer ([08092b1](https://github.com/sapphiredev/rk/commit/08092b196f63fd4eb7233c8763fe7aad1b301c1c))
-   added some minor QoL features, and a lot of docs ([#84](https://github.com/sapphiredev/rk/issues/84)) ([909efb7](https://github.com/sapphi/sapphiredev/it/909efb77b6cec8fb2aeb868c435eb9ef4e4e3fff))
-   async login plugin hooks ([#46](https://github.com/sapphiredev/rk/issues/46)) ([95be214](https://github.com/sapphi/sapphiredev/it/95be214d4932cfca53948803398e4ba144a6fed0))
-   implement additional parsing methods for core arguments ([#82](https://github.com/sapphiredev/rk/issues/82)) ([33dc791](https://github.com/sapphi/sapphiredev/it/33dc791e2b948d2bea1fb4574dfeb87577b7d990))
-   pass error into Events.CommandDenied ([#77](https://github.com/sapphiredev/rk/issues/77)) ([d329b0f](https://github.com/sapphi/sapphiredev/it/d329b0f4f3e41a6050408a32899a98c4a49bd0bd))
-   **args:** add Args#repeat ([5924a53](https://github.com/sapphiredev/rk/commit/5924a53edeb1daea3046c8198e7798dc8932402c))
-   **args:** add overload for IArgument ([#39](https://github.com/sapphiredev/rk/issues/39)) ([0adac4b](https://github.com/sapphi/sapphiredev/it/0adac4bab425fb09e5c82bb177e5fc1f0819bf4b))
-   **client:** move auto-register to registerUserDirectories ([cbb7667](https://github.com/sapphiredev/rk/commit/cbb7667f14cc595cd1cfc4de92f65074cdc77df6))
-   **client:** register and load stores ([#31](https://github.com/sapphiredev/rk/issues/31)) ([db581a9](https://github.com/sapphi/sapphiredev/it/db581a9bf2e140893da8ca3b09e8849bd35d6980))
-   **core:** add base i18n handlers ([#43](https://github.com/sapphiredev/rk/issues/43)) ([a83b77a](https://github.com/sapphi/sapphiredev/it/a83b77a54211ff9594384bd3b0afa1014f530ffa))
-   **core:** added logger ([#38](https://github.com/sapphiredev/rk/issues/38)) ([021085c](https://github.com/sapphi/sapphiredev/it/021085c58c4138f843fd51bde3b29764fd77d5f3))
-   **events:** add commandSuccess, change commandFinish ([#65](https://github.com/sapphiredev/rk/issues/65)) ([0d107e4](https://github.com/sapphi/sapphiredev/it/0d107e4a49c4073db1fc90b808db169eb0860cc9))
-   **flags:** Add flag parsing ([#47](https://github.com/sapphiredev/rk/issues/47)) ([905d1fc](https://github.com/sapphi/sapphiredev/it/905d1fc650bebf203b85ddf70f3d1467a2672ffd))
-   **index:** re-export useful exports from @sapphire/pieces ([#40](https://github.com/sapphiredev/rk/issues/40)) ([d89ee44](https://github.com/sapphi/sapphiredev/it/d89ee445373420531f950978a5e786c9a02c786e))
-   **loader:** automatically register client's directories ([ff86b04](https://github.com/sapphiredev/rk/commit/ff86b0484f79d605295bd96ce0b1c28a147a10ed))
-   commands and command store ([#2](https://github.com/sapphiredev/rk/issues/2)) ([73cdf0e](https://github.com/sapphi/sapphiredev/it/73cdf0e9dfc89c1135cfd47405abc93c0a955b95))
-   finish command handler ([#29](https://github.com/sapphiredev/rk/issues/29)) ([a890d74](https://github.com/sapphi/sapphiredev/it/a890d74dd0b726454a56d5586265e3d708c9b419))
-   implement monitors ([#1](https://github.com/sapphiredev/rk/issues/1)) ([9fde455](https://github.com/sapphi/sapphiredev/it/9fde45586fc96dfd3e8a2d6f5b88527a356978c7))
-   initial work in precondition runners ([bd2be01](https://github.com/sapphiredev/rk/commit/bd2be01b0709c84f7c6b3010e2ae8e80bc623903))
-   more events ([7f7be02](https://github.com/sapphiredev/rk/commit/7f7be02bbcb3cdb894c7777525450f58933c7205))
-   plugin support ([#28](https://github.com/sapphiredev/rk/issues/28)) ([a992b7e](https://github.com/sapphi/sapphiredev/it/a992b7eea17b27c92e39cd10b20d406cc283c3be))
-   type documented events ([#25](https://github.com/sapphiredev/rk/issues/25)) ([df95f00](https://github.com/sapphi/sapphiredev/it/df95f003420c33f8b78729864d31eee6cc8e527a))
-   **Monitor:** add decorators ([#7](https://github.com/sapphiredev/rk/issues/7)) ([5d3accd](https://github.com/sapphi/sapphiredev/it/5d3accd04ef60bcb3f6b48f7507e7ff42ae043fd))

### Bug Fixes

-   renamed `Events.SharedReady` -> `Events.ShardReady` ([#107](https://github.com/sapphiredev/rk/issues/107)) ([d8ca2c0](https://github.com/sapphi/sapphiredev/it/d8ca2c0dbf754e66b661b33efb4496765a30003e))
-   **args:** add boolean to ArgType ([#97](https://github.com/sapphiredev/rk/issues/97)) ([67b4da8](https://github.com/sapphi/sapphiredev/it/67b4da856a2d12aae5e9902e2d0669c66ac9289a))
-   **events:** Return early in CorePreCommandRun if the command is not enabled ([#99](https://github.com/sapphiredev/rk/issues/99)) ([7ac3ba0](https://github.com/sapphi/sapphiredev/it/7ac3ba06ef1a5d1723f5b74abd583c4eb1d63237))
-   argument undefined error ([#34](https://github.com/sapphiredev/rk/issues/34)) ([23de1b2](https://github.com/sapphi/sapphiredev/it/23de1b24d81fb6468f4d9662d0064abc53a08747))
-   do not run disabled commands ([#78](https://github.com/sapphiredev/rk/issues/78)) ([a24175c](https://github.com/sapphi/sapphiredev/it/a24175ca138fa552fb5a250389e83a5206c4db34))
-   failing command tests ([#24](https://github.com/sapphiredev/rk/issues/24)) ([ceeb286](https://github.com/sapphi/sapphiredev/it/ceeb286ec2f0abcc68733f84ec421ca45522af88))
-   make tests pass ([3068899](https://github.com/sapphiredev/rk/commit/3068899deb13fed3a12311a1eeb91b6a10d97615))
-   remove bug breaking prefixless commands ([#80](https://github.com/sapphiredev/rk/issues/80)) ([fc40a6c](https://github.com/sapphi/sapphiredev/it/fc40a6c87ce823f1f360ae199f919cc2e1af0eb7))
-   resolved bug where all pieces were nameless ([989e0c7](https://github.com/sapphiredev/rk/commit/989e0c781e7ced5fc27a6dd59b5980dfc2271ccf))
-   resolved build errors ([09bb56f](https://github.com/sapphiredev/rk/commit/09bb56f3eb088fcd6bf23f25db221e8f978190ab))
-   small docs inconsistency ([#87](https://github.com/sapphiredev/rk/issues/87)) ([f560742](https://github.com/sapphi/sapphiredev/it/f56074209b8e4164b8dd831bff9cc14f8ca19ae2))
-   small typo ([#53](https://github.com/sapphiredev/rk/issues/53)) ([cee4a77](https://github.com/sapphi/sapphiredev/it/cee4a77401afe8ebe16110e284637feb53c9b44e))
-   typing error ([#68](https://github.com/sapphiredev/rk/issues/68)) ([961c33b](https://github.com/sapphi/sapphiredev/it/961c33b5269fbc6f8563196d4bc6fb226889e315))
-   **args:** make options optional ([584c6ef](https://github.com/sapphiredev/rk/commit/584c6ef3a9159c384805723b81ea61bbe659b3e3))
-   **arguments:** error names ([#36](https://github.com/sapphiredev/rk/issues/36)) ([6b3c195](https://github.com/sapphi/sapphiredev/it/6b3c195070db58ff21420affe2bdf15c3ec0cc64))
-   **command-handler:** handle command name resolution better ([0c868e1](https://github.com/sapphiredev/rk/commit/0c868e1f4fc32df7e20333096ba125e473b6e7ef))
-   **command-handler:** make checks more strict ([#62](https://github.com/sapphiredev/rk/issues/62)) ([77352e8](https://github.com/sapphi/sapphiredev/it/77352e8535c7424bb0fccb90a82e6d3895664f9c))
-   **command-handler:** pass parameters through all events ([44cfe86](https://github.com/sapphiredev/rk/commit/44cfe86c2b06106a8f51750afafd2ff7d6e7849a))
-   **command-handler:** use the right variable ([a12e61e](https://github.com/sapphiredev/rk/commit/a12e61ef04b93f88378788bbfaf3013062d6d449))
-   **core:** arguments docs ([#44](https://github.com/sapphiredev/rk/issues/44)) ([1421c05](https://github.com/sapphi/sapphiredev/it/1421c056dc4845f8ed57a893acc0085453b76e0d))
-   **eslint:** cast idOffset to a number ([923bf43](https://github.com/sapphiredev/rk/commit/923bf43f47ea15e1da4f8b507c9bda1dce9d06ff))
-   **event:** set emitter to client if unset ([a3bb96e](https://github.com/sapphiredev/rk/commit/a3bb96eac5df335958f5d068754e2e703aba96a2))

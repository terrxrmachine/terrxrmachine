---- Minecraft Crash Report ----
// This doesn't make any sense!

Time: 2023-10-28 22:11:18
Description: Watching Server

java.lang.Error: ServerHangWatchdog detected that a single server tick took 60.00 seconds (should be max 0.05)
	at net.minecraft.util.CubicSpline$Multipoint.m_216143_(CubicSpline.java:88) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.CubicSpline$Multipoint.m_211396_(CubicSpline.java:213) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.CubicSpline$Multipoint.m_211586_(CubicSpline.java:216) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.CubicSpline$Multipoint$$Lambda$15284/0x0000000802b5e8c0.apply(Unknown Source) ~[?:?] {}
	at java.util.stream.ReferencePipeline$3$1.accept(ReferencePipeline.java:197) ~[?:?] {}
	at java.util.AbstractList$RandomAccessSpliterator.forEachRemaining(AbstractList.java:720) ~[?:?] {}
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?] {}
	at java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:499) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:575) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluateToArrayNode(AbstractPipeline.java:260) ~[?:?] {}
	at java.util.stream.ReferencePipeline.toArray(ReferencePipeline.java:616) ~[?:?] {}
	at java.util.stream.ReferencePipeline.toArray(ReferencePipeline.java:622) ~[?:?] {}
	at java.util.stream.ReferencePipeline.toList(ReferencePipeline.java:627) ~[?:?] {}
	at net.minecraft.util.CubicSpline$Multipoint.m_211396_(CubicSpline.java:216) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Spline.m_207456_(DensityFunctions.java:1221) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice.m_207456_(DensityFunctions.java:741) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice.m_207456_(DensityFunctions.java:741) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice.m_207456_(DensityFunctions.java:741) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity.m_207456_(DensityFunctions.java:850) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Mapped.m_207456_(DensityFunctions.java:954) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Mapped.m_207456_(DensityFunctions.java:896) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.NoiseChunk.<init>(NoiseChunk.java:190) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator.m_224239_(NoiseBasedChunkGenerator.java:199) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citadel.mixins.json:NoiseBasedChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator.m_214096_(NoiseBasedChunkGenerator.java:125) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citadel.mixins.json:NoiseBasedChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223235_(ChunkGeneratorMixin.java:579) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.levelgen.structure.Structure.m_226585_(Structure.java:102) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,xf:fml:forge:structure,re:classloading,xf:fml:forge:structure}
	at net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure.m_214086_(BuriedTreasureStructure.java:21) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.structure.Structure.m_262864_(Structure.java:156) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,xf:fml:forge:structure,re:classloading,xf:fml:forge:structure}
	at net.minecraft.world.level.levelgen.structure.StructureCheck.m_226755_(StructureCheck.java:105) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.structure.StructureCheck.m_226725_(StructureCheck.java:92) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.structure.StructureCheck$$Lambda$18898/0x00000008030fb8f0.get(Unknown Source) ~[?:?] {}
	at it.unimi.dsi.fastutil.longs.Long2BooleanOpenHashMap.computeIfAbsent(Long2BooleanOpenHashMap.java:449) ~[fastutil-8.5.9.jar%23124!/:?] {}
	at net.minecraft.world.level.levelgen.structure.StructureCheck.m_226729_(StructureCheck.java:91) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.StructureManager.m_220473_(StructureManager.java:165) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223198_(ChunkGeneratorMixin.java:248) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223188_(ChunkGeneratorMixin.java:235) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223037_(ChunkGeneratorMixin.java:175) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.level.ServerLevel.m_215011_(ServerLevelMixin.java:1129) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.level.ServerLevelMixin,pl:mixin:APP:citadel.mixins.json:ServerLevelMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:activationrange.ServerWorldMixin_ActivationRange,pl:mixin:APP:create.mixins.json:accessor.ServerLevelAccessor,pl:mixin:A,pl:arclight_implementer:async,pl:arclight_implementer:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction.m_7372_(ExplorationMapFunction.java:76) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction.apply(LootItemConditionalFunction.java:31) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,re:mixin}
	at net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction.apply(LootItemConditionalFunction.java:20) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,re:mixin}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunctions.m_80765_(LootItemFunctions.java:60) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunctions$$Lambda$12840/0x00000008023ae008.apply(Unknown Source) ~[?:?] {}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunction.m_80728_(LootItemFunction.java:14) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,re:mixin}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunction$$Lambda$16717/0x0000000802e4e438.accept(Unknown Source) ~[?:?] {}
	at net.minecraft.world.level.storage.loot.entries.LootItem.m_6948_(LootItem.java:33) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1.m_6941_(LootPoolSingletonContainer.java:59) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.LootPool.m_79058_(LootPool.java:72) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.storage.loot.LootPool.m_79053_(LootPool.java:94) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.storage.loot.LootTable.m_79131_(LootTableMixin.java:85) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.storage.loot.LootTable.m_230922_(LootTableMixin.java:117) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.storage.loot.LootTable.eject$bhc000$arclight$nonPluginEvent(LootTableMixin.java:540) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.storage.loot.LootTable.m_287188_(LootTableMixin.java:139) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity.m_59640_(RandomizableContainerBlockEntity.java:82) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity.m_7208_(RandomizableContainerBlockEntity.java:154) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.server.level.ServerPlayer.m_5893_(ServerPlayerMixin.java:963) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.entity.player.ServerPlayerMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:network.ServerPlayerMixin_Optimize,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.block.ChestBlock.m_6227_(ChestBlockMixin.java:236) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.block.ChestBlockMixin,pl:mixin:A}
	at net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase.m_60664_(BlockBehaviour_BlockStateBaseMixin.java:778) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.block.state.BlockBehaviour_BlockStateBaseMixin,pl:mixin:APP:ferritecore.blockstatecache.mixin.json:BlockStateBaseMixin,pl:mixin:A}
	at net.minecraft.server.level.ServerPlayerGameMode.m_7179_(ServerPlayerGameModeMixin.java:846) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:computing_frames,re:classloading,pl:mixin:APP:mixins.arclight.core.json:server.management.ServerPlayerGameModeMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:realtime.PlayerInteractionManagerMixin_Realtime,pl:mixin:A}
	at net.minecraft.server.network.ServerGamePacketListenerImpl.m_6371_(ServerPlayNetHandlerMixin.java:1055) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:network.ServerPlayNetHandlerMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:network.ServerGamePacketListenerImplMixin_Optimize,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.network.protocol.game.ServerboundUseItemOnPacket.m_5797_(CPlayerTryUseItemOnBlockPacketMixin.java:34) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:classloading,pl:mixin:APP:mixins.arclight.core.json:network.protocol.game.CPlayerTryUseItemOnBlockPacketMixin,pl:mixin:A}
	at net.minecraft.network.protocol.game.ServerboundUseItemOnPacket.m_5797_(CPlayerTryUseItemOnBlockPacketMixin.java:8) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:classloading,pl:mixin:APP:mixins.arclight.core.json:network.protocol.game.CPlayerTryUseItemOnBlockPacketMixin,pl:mixin:A}
	at net.minecraft.network.protocol.PacketUtils.mdc210f6$lambda$ensureRunningOnSameThread$0$0(PacketThreadUtilMixin.java:537) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:classloading,pl:mixin:APP:mixins.arclight.core.json:network.protocol.PacketThreadUtilMixin,pl:mixin:A}
	at net.minecraft.network.protocol.PacketUtils$$Lambda$17251/0x0000000802ef5078.run(Unknown Source) ~[?:?] {}
	at net.minecraft.server.TickTask.run(TickTask.java:18) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.m_6367_(BlockableEventLoop.java:156) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at net.minecraft.util.thread.ReentrantBlockableEventLoop.m_6367_(ReentrantBlockableEventLoop.java:23) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:computing_frames,re:classloading,re:mixin}
	at net.minecraft.server.MinecraftServer.m_6367_(MinecraftServerMixin.java:770) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_6367_(MinecraftServerMixin.java:161) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.util.thread.BlockableEventLoop.m_7245_(BlockableEventLoop.java:130) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_129961_(MinecraftServerMixin.java:753) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_7245_(MinecraftServerMixin.java:747) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.util.thread.BlockableEventLoop.m_18701_(BlockableEventLoop.java:139) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_130012_(MinecraftServerMixin.java:733) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_130011_(MinecraftServerMixin.java:2074) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_206580_(MinecraftServerMixin.java:251) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer$$Lambda$13337/0x000000080242b5f0.run(Unknown Source) ~[?:?] {}
	at java.lang.Thread.run(Thread.java:833) ~[?:?] {re:mixin,re:mixin,re:mixin,re:mixin,re:mixin}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Server Watchdog
Stacktrace:
	at net.minecraft.util.CubicSpline$Multipoint.m_216143_(CubicSpline.java:88) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.CubicSpline$Multipoint.m_211396_(CubicSpline.java:213) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.CubicSpline$Multipoint.m_211586_(CubicSpline.java:216) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.CubicSpline$Multipoint$$Lambda$15284/0x0000000802b5e8c0.apply(Unknown Source) ~[?:?] {}
	at java.util.stream.ReferencePipeline$3$1.accept(ReferencePipeline.java:197) ~[?:?] {}
	at java.util.AbstractList$RandomAccessSpliterator.forEachRemaining(AbstractList.java:720) ~[?:?] {}
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?] {}
	at java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:499) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:575) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluateToArrayNode(AbstractPipeline.java:260) ~[?:?] {}
	at java.util.stream.ReferencePipeline.toArray(ReferencePipeline.java:616) ~[?:?] {}
	at java.util.stream.ReferencePipeline.toArray(ReferencePipeline.java:622) ~[?:?] {}
	at java.util.stream.ReferencePipeline.toList(ReferencePipeline.java:627) ~[?:?] {}
	at net.minecraft.util.CubicSpline$Multipoint.m_211396_(CubicSpline.java:216) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Spline.m_207456_(DensityFunctions.java:1221) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice.m_207456_(DensityFunctions.java:741) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice.m_207456_(DensityFunctions.java:741) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice.m_207456_(DensityFunctions.java:741) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity.m_207456_(DensityFunctions.java:850) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd.m_207456_(DensityFunctions.java:1097) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Mapped.m_207456_(DensityFunctions.java:954) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Mapped.m_207456_(DensityFunctions.java:896) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207456_(DensityFunctions.java:1179) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked.m_207456_(DensityFunctions.java:428) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.NoiseChunk.<init>(NoiseChunk.java:190) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator.m_224239_(NoiseBasedChunkGenerator.java:199) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citadel.mixins.json:NoiseBasedChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator.m_214096_(NoiseBasedChunkGenerator.java:125) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citadel.mixins.json:NoiseBasedChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223235_(ChunkGeneratorMixin.java:579) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.levelgen.structure.Structure.m_226585_(Structure.java:102) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,xf:fml:forge:structure,re:classloading,xf:fml:forge:structure}
	at net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure.m_214086_(BuriedTreasureStructure.java:21) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.structure.Structure.m_262864_(Structure.java:156) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,xf:fml:forge:structure,re:classloading,xf:fml:forge:structure}
	at net.minecraft.world.level.levelgen.structure.StructureCheck.m_226755_(StructureCheck.java:105) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.structure.StructureCheck.m_226725_(StructureCheck.java:92) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.levelgen.structure.StructureCheck$$Lambda$18898/0x00000008030fb8f0.get(Unknown Source) ~[?:?] {}
	at it.unimi.dsi.fastutil.longs.Long2BooleanOpenHashMap.computeIfAbsent(Long2BooleanOpenHashMap.java:449) ~[fastutil-8.5.9.jar%23124!/:?] {}
	at net.minecraft.world.level.levelgen.structure.StructureCheck.m_226729_(StructureCheck.java:91) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.StructureManager.m_220473_(StructureManager.java:165) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223198_(ChunkGeneratorMixin.java:248) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223188_(ChunkGeneratorMixin.java:235) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.chunk.ChunkGenerator.m_223037_(ChunkGeneratorMixin.java:175) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.chunk.ChunkGeneratorMixin,pl:mixin:APP:citadel.mixins.json:ChunkGeneratorMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.level.ServerLevel.m_215011_(ServerLevelMixin.java:1129) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.level.ServerLevelMixin,pl:mixin:APP:citadel.mixins.json:ServerLevelMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:activationrange.ServerWorldMixin_ActivationRange,pl:mixin:APP:create.mixins.json:accessor.ServerLevelAccessor,pl:mixin:A,pl:arclight_implementer:async,pl:arclight_implementer:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction.m_7372_(ExplorationMapFunction.java:76) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction.apply(LootItemConditionalFunction.java:31) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,re:mixin}
	at net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction.apply(LootItemConditionalFunction.java:20) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,re:mixin}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunctions.m_80765_(LootItemFunctions.java:60) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunctions$$Lambda$12840/0x00000008023ae008.apply(Unknown Source) ~[?:?] {}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunction.m_80728_(LootItemFunction.java:14) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,re:mixin}
	at net.minecraft.world.level.storage.loot.functions.LootItemFunction$$Lambda$16717/0x0000000802e4e438.accept(Unknown Source) ~[?:?] {}
	at net.minecraft.world.level.storage.loot.entries.LootItem.m_6948_(LootItem.java:33) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1.m_6941_(LootPoolSingletonContainer.java:59) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.world.level.storage.loot.LootPool.m_79058_(LootPool.java:72) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.storage.loot.LootPool.m_79053_(LootPool.java:94) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.storage.loot.LootTable.m_79131_(LootTableMixin.java:85) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.storage.loot.LootTable.m_230922_(LootTableMixin.java:117) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.storage.loot.LootTable.eject$bhc000$arclight$nonPluginEvent(LootTableMixin.java:540) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.storage.loot.LootTable.m_287188_(LootTableMixin.java:139) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.storage.loot.LootTableMixin,pl:mixin:A}
	at net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity.m_59640_(RandomizableContainerBlockEntity.java:82) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity.m_7208_(RandomizableContainerBlockEntity.java:154) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.server.level.ServerPlayer.m_5893_(ServerPlayerMixin.java:963) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.entity.player.ServerPlayerMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:network.ServerPlayerMixin_Optimize,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.world.level.block.ChestBlock.m_6227_(ChestBlockMixin.java:236) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.block.ChestBlockMixin,pl:mixin:A}
	at net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase.m_60664_(BlockBehaviour_BlockStateBaseMixin.java:778) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:world.level.block.state.BlockBehaviour_BlockStateBaseMixin,pl:mixin:APP:ferritecore.blockstatecache.mixin.json:BlockStateBaseMixin,pl:mixin:A}
	at net.minecraft.server.level.ServerPlayerGameMode.m_7179_(ServerPlayerGameModeMixin.java:846) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:computing_frames,re:classloading,pl:mixin:APP:mixins.arclight.core.json:server.management.ServerPlayerGameModeMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:realtime.PlayerInteractionManagerMixin_Realtime,pl:mixin:A}
	at net.minecraft.server.network.ServerGamePacketListenerImpl.m_6371_(ServerPlayNetHandlerMixin.java:1055) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:network.ServerPlayNetHandlerMixin,pl:mixin:APP:mixins.arclight.impl.forge.optimization.json:network.ServerGamePacketListenerImplMixin_Optimize,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.network.protocol.game.ServerboundUseItemOnPacket.m_5797_(CPlayerTryUseItemOnBlockPacketMixin.java:34) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:classloading,pl:mixin:APP:mixins.arclight.core.json:network.protocol.game.CPlayerTryUseItemOnBlockPacketMixin,pl:mixin:A}
	at net.minecraft.network.protocol.game.ServerboundUseItemOnPacket.m_5797_(CPlayerTryUseItemOnBlockPacketMixin.java:8) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:classloading,pl:mixin:APP:mixins.arclight.core.json:network.protocol.game.CPlayerTryUseItemOnBlockPacketMixin,pl:mixin:A}
	at net.minecraft.network.protocol.PacketUtils.mdc210f6$lambda$ensureRunningOnSameThread$0$0(PacketThreadUtilMixin.java:537) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:classloading,pl:mixin:APP:mixins.arclight.core.json:network.protocol.PacketThreadUtilMixin,pl:mixin:A}
	at net.minecraft.network.protocol.PacketUtils$$Lambda$17251/0x0000000802ef5078.run(Unknown Source) ~[?:?] {}
	at net.minecraft.server.TickTask.run(TickTask.java:18) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.m_6367_(BlockableEventLoop.java:156) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at net.minecraft.util.thread.ReentrantBlockableEventLoop.m_6367_(ReentrantBlockableEventLoop.java:23) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,re:computing_frames,re:classloading,re:mixin}
	at net.minecraft.server.MinecraftServer.m_6367_(MinecraftServerMixin.java:770) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_6367_(MinecraftServerMixin.java:161) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.util.thread.BlockableEventLoop.m_7245_(BlockableEventLoop.java:130) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_129961_(MinecraftServerMixin.java:753) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_7245_(MinecraftServerMixin.java:747) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.util.thread.BlockableEventLoop.m_18701_(BlockableEventLoop.java:139) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_130012_(MinecraftServerMixin.java:733) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_130011_(MinecraftServerMixin.java:2074) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
	at net.minecraft.server.MinecraftServer.m_206580_(MinecraftServerMixin.java:251) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.arclight.core.json:server.MinecraftServerMixin,pl:mixin:APP:citadel.mixins.json:MinecraftServerMixin,pl:mixin:APP:balm.mixins.json:MinecraftServerMixin,pl:mixin:A,re:mixin,pl:accesstransformer:B}
-- Thread Dump --
Details:
	Threads: "Reference Handler" daemon prio=10 Id=2 RUNNABLE
	at java.base@18.0.2-ea/java.lang.ref.Reference.waitForReferencePendingList(Native Method)
	at java.base@18.0.2-ea/java.lang.ref.Reference.processPendingReferences(Reference.java:253)
	at java.base@18.0.2-ea/java.lang.ref.Reference$ReferenceHandler.run(Reference.java:215)


"Finalizer" daemon prio=8 Id=3 WAITING on java.lang.ref.ReferenceQueue$Lock@751d38b2
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.lang.ref.ReferenceQueue$Lock@751d38b2
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155)
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:176)
	at java.base@18.0.2-ea/java.lang.ref.Finalizer$FinalizerThread.run(Finalizer.java:183)


"Signal Dispatcher" daemon prio=9 Id=4 RUNNABLE


"Notification Thread" daemon prio=9 Id=11 RUNNABLE


"Common-Cleaner" daemon prio=8 Id=12 TIMED_WAITING on java.lang.ref.ReferenceQueue$Lock@7bdad861
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.lang.ref.ReferenceQueue$Lock@7bdad861
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155)
	at java.base@18.0.2-ea/jdk.internal.ref.CleanerImpl.run(CleanerImpl.java:140)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)
	at java.base@18.0.2-ea/jdk.internal.misc.InnocuousThread.run(InnocuousThread.java:162)


"Log4j2-AsyncAppenderEventDispatcher-1-Async" daemon prio=5 Id=19 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@7fe553c2
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@7fe553c2
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ArrayBlockingQueue.take(ArrayBlockingQueue.java:420)
	at MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.appender.AsyncAppenderEventDispatcher.dispatchAll(AsyncAppenderEventDispatcher.java:82)
	...


"JNA Cleaner" daemon prio=5 Id=21 WAITING on java.lang.ref.ReferenceQueue$Lock@3ae7d25a
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.lang.ref.ReferenceQueue$Lock@3ae7d25a
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155)
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:176)
	at MC-BOOTSTRAP/com.sun.jna@5.12.1/com.sun.jna.internal.Cleaner$1.run(Cleaner.java:58)


"Timer hack thread" daemon prio=5 Id=22 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at TRANSFORMER/minecraft@1.20.1/net.minecraft.Util$9.run(Util.java:672)


"Thread-1" daemon prio=5 Id=29 TIMED_WAITING
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:376)
	at MC-BOOTSTRAP/com.electronwill.nightconfig.core@3.6.4/com.electronwill.nightconfig.core.file.FileWatcher$WatcherThread.run(FileWatcher.java:190)


"FileSystemWatchService" daemon prio=5 Id=30 RUNNABLE (in native)
	at java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService.poll(Native Method)
	at java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService$Poller.run(LinuxWatchService.java:314)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Yggdrasil Key Fetcher" daemon prio=5 Id=37 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@2623a51c
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@2623a51c
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"Worker-Main-1" daemon prio=5 Id=39 WAITING on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1724)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"Worker-Main-3" daemon prio=5 Id=41 WAITING on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1724)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"Worker-Main-4" daemon prio=5 Id=42 TIMED_WAITING on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"Worker-Main-5" daemon prio=5 Id=43 WAITING on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@b976869
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1724)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"Server thread" prio=8 Id=44 RUNNABLE
	at TRANSFORMER/minecraft@1.20.1/net.minecraft.util.CubicSpline$Multipoint.m_216143_(CubicSpline.java:88)
	at TRANSFORMER/minecraft@1.20.1/net.minecraft.util.CubicSpline$Multipoint.m_211396_(CubicSpline.java:213)
	at TRANSFORMER/minecraft@1.20.1/net.minecraft.util.CubicSpline$Multipoint.m_211586_(CubicSpline.java:216)
	at TRANSFORMER/minecraft@1.20.1/net.minecraft.util.CubicSpline$Multipoint$$Lambda$15284/0x0000000802b5e8c0.apply(Unknown Source)
	at java.base@18.0.2-ea/java.util.stream.ReferencePipeline$3$1.accept(ReferencePipeline.java:197)
	at java.base@18.0.2-ea/java.util.AbstractList$RandomAccessSpliterator.forEachRemaining(AbstractList.java:720)
	at java.base@18.0.2-ea/java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509)
	at java.base@18.0.2-ea/java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:499)
	...


"Server console handler" daemon prio=8 Id=46 RUNNABLE
	at java.base@18.0.2-ea/java.io.FileInputStream.read0(Native Method)
	at java.base@18.0.2-ea/java.io.FileInputStream.read(FileInputStream.java:228)
	at MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.terminal.impl.AbstractPty$PtyInputStream.read(AbstractPty.java:73)
	at MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.utils.NonBlockingInputStream.read(NonBlockingInputStream.java:62)
	at MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.utils.NonBlocking$NonBlockingInputStreamReader.read(NonBlocking.java:168)
	at MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.utils.NonBlockingReader.read(NonBlockingReader.java:57)
	at MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.keymap.BindingReader.readCharacter(BindingReader.java:133)
	at MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.keymap.BindingReader.readBinding(BindingReader.java:110)
	...


"DestroyJavaVM" prio=5 Id=47 RUNNABLE


"Netty Epoll Server IO #0" daemon prio=8 Id=48 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Java2D Disposer" daemon prio=10 Id=49 WAITING on java.lang.ref.ReferenceQueue$Lock@5eb9419a
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.lang.ref.ReferenceQueue$Lock@5eb9419a
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155)
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:176)
	at java.desktop@18.0.2-ea/sun.java2d.Disposer.run(Disposer.java:145)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"mysql-cj-abandoned-connection-cleanup" daemon prio=8 Id=51 TIMED_WAITING on java.lang.ref.ReferenceQueue$Lock@5ac82d15
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.lang.ref.ReferenceQueue$Lock@5ac82d15
	at java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155)
	at MC-BOOTSTRAP/mysql.connector.j@8.0.33/com.mysql.cj.jdbc.AbandonedConnectionCleanupThread.run(AbandonedConnectionCleanupThread.java:91)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1136)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)

	Number of locked synchronizers = 1
	- java.util.concurrent.ThreadPoolExecutor$Worker@29430951


"Spigot Metrics Thread" daemon prio=8 Id=52 TIMED_WAITING on java.util.TaskQueue@61f87815
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.util.TaskQueue@61f87815
	at java.base@18.0.2-ea/java.util.TimerThread.mainLoop(Timer.java:563)
	at java.base@18.0.2-ea/java.util.TimerThread.run(Timer.java:516)


"arclight class cache saving thread" daemon prio=8 Id=53 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@511c9063
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@511c9063
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"DiscordSRV ExpiryThread" prio=8 Id=57 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at github.scarsz.discordsrv.objects.ExpiringDualHashBidiMap$ExpiryThread.run(ExpiringDualHashBidiMap.java:132)


"WorldEdit Session Manager" prio=8 Id=67 TIMED_WAITING on java.util.TaskQueue@45bdae4b
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.util.TaskQueue@45bdae4b
	at java.base@18.0.2-ea/java.util.TimerThread.mainLoop(Timer.java:563)
	at java.base@18.0.2-ea/java.util.TimerThread.run(Timer.java:516)


"bStats-Metrics" prio=8 Id=69 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@5e86936c
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@5e86936c
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"bStats-Metrics" prio=8 Id=70 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@7c9c7079
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@7c9c7079
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"FileSystemWatchService" daemon prio=8 Id=73 RUNNABLE (in native)
	at java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService.poll(Native Method)
	at java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService$Poller.run(LinuxWatchService.java:314)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"bStats-Metrics" prio=8 Id=75 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@49366801
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@49366801
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"bStats-Metrics" prio=8 Id=81 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@61d1589a
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@61d1589a
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"pool-14-thread-1" prio=5 Id=82 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@ba6ba3f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@ba6ba3f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"bStats-Metrics" prio=8 Id=83 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@14261c8a
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@14261c8a
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"pool-16-thread-1" prio=5 Id=85 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@6eaa186f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@6eaa186f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"Thread-10" prio=8 Id=87 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at net.coreprotect.thread.CacheHandler.run(CacheHandler.java:30)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Thread-11" prio=8 Id=88 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at net.coreprotect.consumer.Consumer.run(Consumer.java:131)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"bStats-Metrics" prio=8 Id=89 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@55488a8
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@55488a8
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"DiscordSRV - JDA Rate Limit" prio=5 Id=91 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1170)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	...


"DiscordSRV - JDA Rate Limit" prio=5 Id=92 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	...


"DiscordSRV - JDA Rate Limit" prio=5 Id=100 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"DiscordSRV - JDA Gateway" prio=5 Id=103 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@1f7b34da
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@1f7b34da
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"JDA MainWS-ReadThread" prio=8 Id=109 RUNNABLE (in native)
	at java.base@18.0.2-ea/sun.nio.ch.Net.poll(Native Method)
	at java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.park(NioSocketImpl.java:178)
	at java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.timedRead(NioSocketImpl.java:282)
	at java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.implRead(NioSocketImpl.java:306)
	at java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.read(NioSocketImpl.java:347)
	at java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl$1.read(NioSocketImpl.java:800)
	at java.base@18.0.2-ea/java.net.Socket$SocketInputStream.read(Socket.java:966)
	at java.base@18.0.2-ea/sun.security.ssl.SSLSocketInputRecord.read(SSLSocketInputRecord.java:478)
	...

	Number of locked synchronizers = 2
	- java.util.concurrent.locks.ReentrantLock$NonfairSync@1ce37f
	- java.util.concurrent.locks.ReentrantLock$NonfairSync@563cc056


"JDA MainWS-WriteThread" prio=8 Id=110 WAITING on github.scarsz.discordsrv.dependencies.ws.client.WritingThread@1027f3af
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on github.scarsz.discordsrv.dependencies.ws.client.WritingThread@1027f3af
	at java.base@18.0.2-ea/java.lang.Object.wait(Object.java:338)
	at github.scarsz.discordsrv.dependencies.ws.client.WritingThread.waitForFrames(WritingThread.java:305)
	at github.scarsz.discordsrv.dependencies.ws.client.WritingThread.main(WritingThread.java:89)
	at github.scarsz.discordsrv.dependencies.ws.client.WritingThread.runMain(WritingThread.java:55)
	at github.scarsz.discordsrv.dependencies.ws.client.WebSocketThread.run(WebSocketThread.java:45)


"DiscordSRV - Presence Updater" prio=8 Id=111 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at github.scarsz.discordsrv.objects.threads.PresenceUpdater.run(PresenceUpdater.java:117)


"DiscordSRV - Nickname Updater" prio=8 Id=112 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at github.scarsz.discordsrv.objects.threads.NicknameUpdater.run(NicknameUpdater.java:104)


"pool-19-thread-1" prio=5 Id=113 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@50bad27f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@50bad27f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"DiscordSRV - Server Watchdog" prio=8 Id=114 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at github.scarsz.discordsrv.objects.threads.ServerWatchdog.run(ServerWatchdog.java:63)


"DiscordSRV - Channel Topic Updater" prio=8 Id=115 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at github.scarsz.discordsrv.objects.threads.ChannelTopicUpdater.run(ChannelTopicUpdater.java:54)


"DiscordSRV - Channel Updater" prio=8 Id=116 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at github.scarsz.discordsrv.objects.threads.ChannelUpdater.run(ChannelUpdater.java:93)


"bStats-Metrics" prio=8 Id=117 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@375ad40c
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@375ad40c
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"DiscordSRV - JDA Rate Limit" prio=5 Id=118 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	...


"DiscordSRV - JDA Rate Limit" prio=5 Id=119 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3b1dad7f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"Netty Epoll Server IO #1" daemon prio=8 Id=120 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait0(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:182)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWait(EpollEventLoop.java:302)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:366)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Server Watchdog" daemon prio=8 Id=121 RUNNABLE
	at java.management@18.0.2-ea/sun.management.ThreadImpl.dumpThreads0(Native Method)
	at java.management@18.0.2-ea/sun.management.ThreadImpl.dumpAllThreads(ThreadImpl.java:521)
	at java.management@18.0.2-ea/sun.management.ThreadImpl.dumpAllThreads(ThreadImpl.java:509)
	at TRANSFORMER/minecraft@1.20.1/net.minecraft.server.dedicated.ServerWatchdog.run(ServerWatchdog.java:41)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Thread-28" prio=8 Id=127 TIMED_WAITING
	at java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method)
	at net.coreprotect.thread.NetworkHandler.run(NetworkHandler.java:360)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Log4j2-AsyncAppenderEventDispatcher-2-Async" daemon prio=5 Id=134 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@7d49cc1
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@7d49cc1
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ArrayBlockingQueue.take(ArrayBlockingQueue.java:420)
	at MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.appender.AsyncAppenderEventDispatcher.dispatchAll(AsyncAppenderEventDispatcher.java:82)
	...


"Netty Epoll Server IO #2" daemon prio=8 Id=140 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Netty Epoll Server IO #3" daemon prio=8 Id=141 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Netty Epoll Server IO #4" daemon prio=8 Id=142 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"pool-13-thread-1" prio=5 Id=144 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	...


"pool-13-thread-2" prio=5 Id=145 TIMED_WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	...


"pool-13-thread-3" prio=5 Id=146 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	...


"pool-13-thread-4" prio=5 Id=147 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@28c1bd1f
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177)
	at java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899)
	...


"Netty Epoll Server IO #5" daemon prio=8 Id=233 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Netty Epoll Server IO #6" daemon prio=8 Id=236 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"fawe-clipboard-0" prio=5 Id=264 WAITING on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@2eeebb52
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@2eeebb52
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435)
	at java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.LinkedBlockingQueue.take(LinkedBlockingQueue.java:435)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062)
	...


"Netty Epoll Server IO #7" daemon prio=8 Id=266 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Netty Epoll Server IO #8" daemon prio=8 Id=283 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Netty Epoll Server IO #9" daemon prio=8 Id=284 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Netty Epoll Server IO #10" daemon prio=8 Id=352 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"IO-Worker-34" prio=8 Id=369 TIMED_WAITING on java.util.concurrent.SynchronousQueue$TransferStack@4ff5f037
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.SynchronousQueue$TransferStack@4ff5f037
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"IO-Worker-36" prio=8 Id=385 TIMED_WAITING on java.util.concurrent.SynchronousQueue$TransferStack@4ff5f037
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.SynchronousQueue$TransferStack@4ff5f037
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"IO-Worker-39" prio=8 Id=456 TIMED_WAITING on java.util.concurrent.SynchronousQueue$TransferStack@4ff5f037
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.SynchronousQueue$TransferStack@4ff5f037
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"OkHttp ConnectionPool" daemon prio=5 Id=478 TIMED_WAITING on java.util.concurrent.SynchronousQueue$TransferStack@6ce44f9c
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.SynchronousQueue$TransferStack@6ce44f9c
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401)
	at java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122)
	at java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)


"Okio Watchdog" daemon prio=5 Id=479 TIMED_WAITING on java.lang.Class@7068e671
	at java.base@18.0.2-ea/java.lang.Object.wait(Native Method)
	-  waiting on java.lang.Class@7068e671
	at github.scarsz.discordsrv.dependencies.okio.AsyncTimeout.awaitTimeout(AsyncTimeout.java:348)
	at github.scarsz.discordsrv.dependencies.okio.AsyncTimeout$Watchdog.run(AsyncTimeout.java:313)


"DiscordSRV - JDA Callback 0" daemon prio=5 Id=480 TIMED_WAITING on java.util.concurrent.ForkJoinPool@49e83e5a
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@49e83e5a
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"ForkJoinPool.commonPool-worker-36" daemon prio=5 Id=489 TIMED_WAITING on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"ForkJoinPool.commonPool-worker-37" daemon prio=5 Id=490 TIMED_WAITING on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"ForkJoinPool.commonPool-worker-38" daemon prio=5 Id=491 TIMED_WAITING on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"ForkJoinPool.commonPool-worker-39" daemon prio=5 Id=492 TIMED_WAITING on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"ForkJoinPool.commonPool-worker-40" daemon prio=5 Id=493 TIMED_WAITING on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method)
	-  waiting on java.util.concurrent.ForkJoinPool@1287381e
	at java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623)
	at java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)


"Netty Epoll Server IO #11" daemon prio=8 Id=494 RUNNABLE (in native)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait0(Native Method)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:182)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWait(EpollEventLoop.java:302)
	at MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:366)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)



Stacktrace:
	at net.minecraft.server.dedicated.ServerWatchdog.run(ServerWatchdog.java:56) ~[server-1.20.1-20230612.114412-srg.jar%23215!/:?] {re:classloading}
	at java.lang.Thread.run(Thread.java:833) ~[?:?] {re:mixin,re:mixin,re:mixin,re:mixin,re:mixin}


-- Performance stats --
Details:
	Random tick rate: 3
	Level stats: ResourceKey[minecraft:dimension / minecraft:overworld]: players: 2, entities: 256,256,110,1179,1179,0,0 [minecraft:item:61,minecraft:falling_block:42,alexsmobs:kangaroo:23,alexsmobs:emu:15,minecraft:skeleton:15], block_entities: 2444 [minecraft:sculk_sensor:1674,minecraft:sculk_catalyst:422,minecraft:sculk_shrieker:206,minecraft:sign:96,minecraft:mob_spawner:35], block_ticks: 29772, fluid_ticks: 20167, chunk_source: Chunks[S] W: 5236 E: 256,256,110,1179,1179,0,0,
ResourceKey[minecraft:dimension / twilightforest:twilight_forest]: players: 0, entities: 0,0,0,0,0,0,0 [], block_entities: 0 [], block_ticks: 0, fluid_ticks: 0, chunk_source: Chunks[S] W: 0 E: 0,0,0,0,0,0,0,
ResourceKey[minecraft:dimension / minecraft:the_nether]: players: 0, entities: 0,0,0,0,0,0,0 [], block_entities: 0 [], block_ticks: 0, fluid_ticks: 0, chunk_source: Chunks[S] W: 0 E: 0,0,0,0,0,0,0,
ResourceKey[minecraft:dimension / minecraft:the_end]: players: 0, entities: 0,0,0,0,0,0,0 [], block_entities: 0 [], block_ticks: 0, fluid_ticks: 0, chunk_source: Chunks[S] W: 0 E: 0,0,0,0,0,0,0

-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Linux (amd64) version 5.15.0-46-generic
	Java Version: 18.0.2-ea, Private Build
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode, sharing), Private Build
	Memory: 2090679128 bytes (1993 MiB) / 4823449600 bytes (4600 MiB) up to 12884901888 bytes (12288 MiB)
	CPUs: 6
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Xeon(R) Platinum 8160 CPU @ 2.10GHz
	Identifier: Intel64 Family 6 Model 85 Stepping 4
	Microarchitecture: Skylake (Server)
	Frequency (GHz): 2.10
	Number of physical packages: 6
	Number of physical CPUs: 6
	Number of logical CPUs: 6
	Graphics card #0 name: GD 5446
	Graphics card #0 vendor: Cirrus Logic (0x1013)
	Graphics card #0 VRAM (MB): 32.00
	Graphics card #0 deviceId: 0x00b8
	Graphics card #0 versionInfo: unknown
	Memory slot #0 capacity (MB): 12288.00
	Memory slot #0 clockSpeed (GHz): -0.00
	Memory slot #0 type: RAM
	Virtual memory max (MB): 7008.49
	Virtual memory used (MB): 12594.41
	Swap memory total (MB): 1023.98
	Swap memory used (MB): 1007.09
	JVM Flags: 2 total; -Xmx12G -Xms1G
	Server Running: true
	Player Count: 2 / 15; [ServerPlayer['A1A2_A1A2'/1466, l='ServerLevel[world]', x=84.35, y=61.71, z=670.44](A1A2_A1A2 at 84.35379854859463,61.714097549774166,670.4409111386141), ServerPlayer['terrxrmachin_e'/1797, l='ServerLevel[world]', x=82.56, y=59.00, z=670.61](terrxrmachin_e at 82.5649933340374,59.0,670.6060553542151)]
	Data Packs: vanilla, mod:elytraslot (incompatible), mod:libipn (incompatible), mod:enchdesc (incompatible), mod:silentlib, mod:caelus (incompatible), mod:kotlinforforge (incompatible), mod:incendium, mod:structorytowers, mod:sophisticatedcore (incompatible), mod:curios (incompatible), mod:flywheel, mod:create, mod:structory, mod:citadel (incompatible), mod:alexsmobs (incompatible), mod:nullscape, mod:bookshelf, mod:sophisticatedbackpacks (incompatible), mod:cfm, mod:ferritecore (incompatible), mod:balm, mod:arclight (incompatible), mod:terralith, mod:forge, mod:silentgear, mod:twilightforest, mod:tflostblocks, mod:ironchest, file/bat membranes v1.0.6 (MC 1.20-1.20.2), file/cauldron concrete v2.0.8 (MC 1.20-1.20.2), file/double shulker shells v1.3.5 (MC 1.20-1.20.2), file/dragon drops v1.3.5 (MC 1.20-1.20.2), file/durability ping v1.1.5 (MC 1.20-1.20.2)
	Enabled Feature Flags: minecraft:vanilla
	World Generation: Experimental
	Is Modded: Definitely; Server brand changed to 'forge arclight/Trials'
	Type: Dedicated Server (map_server.txt)
	ModLauncher: 10.0.9+10.0.9+main.dcd20f30
	ModLauncher launch target: arclightserver
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		arclight-forge-1.20.1-1.0.0.jar arclight_implementer PLUGINSERVICE 
		eventbus-6.0.5.jar eventbus PLUGINSERVICE 
		fmlloader-1.20.1-47.1.1.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.20.1-47.1.1.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.20.1-47.1.1.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.20.1-47.1.1.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.20.1-47.1.1.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.9.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		javafml@null
		kotlinforforge@4.5.0
		lowcodefml@null
	Mod List: 
		server-1.20.1-20230612.114412-srg.jar             |Minecraft                     |minecraft                     |1.20.1              |DONE      |Manifest: NOSIGNATURE
		elytraslot-forge-6.3.0+1.20.1.jar                 |Elytra Slot                   |elytraslot                    |6.3.0+1.20.1        |DONE      |Manifest: NOSIGNATURE
		libIPN-forge-1.20-4.0.0.jar                       |libIPN                        |libipn                        |4.0.0               |DONE      |Manifest: NOSIGNATURE
		EnchantmentDescriptions-Forge-1.20.1-17.0.8.jar   |EnchantmentDescriptions       |enchdesc                      |17.0.8              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		silent-lib-1.20.1-8.0.0.jar                       |Silent Lib                    |silentlib                     |8.0.0               |DONE      |Manifest: NOSIGNATURE
		caelus-forge-3.1.0+1.20.jar                       |Caelus API                    |caelus                        |3.1.0+1.20          |DONE      |Manifest: NOSIGNATURE
		kffmod-4.5.0.jar                                  |Kotlin For Forge              |kotlinforforge                |4.5.0               |DONE      |Manifest: NOSIGNATURE
		Incendium_1.20.2_v5.3.2.jar                       |Incendium                     |incendium                     |5.3.2               |DONE      |Manifest: NOSIGNATURE
		Structory_Towers_1.20.2_v1.0.5.jar                |Structory: Towers             |structorytowers               |1.0.5               |DONE      |Manifest: NOSIGNATURE
		sophisticatedcore-1.20.1-0.5.100.457.jar          |Sophisticated Core            |sophisticatedcore             |0.5.100.457         |DONE      |Manifest: NOSIGNATURE
		curios-forge-5.4.0+1.20.1.jar                     |Curios API                    |curios                        |5.4.0+1.20.1        |DONE      |Manifest: NOSIGNATURE
		flywheel-forge-1.20.1-0.6.10-7.jar                |Flywheel                      |flywheel                      |0.6.10-7            |DONE      |Manifest: NOSIGNATURE
		create-1.20.1-0.5.1.e.jar                         |Create                        |create                        |0.5.1.e             |DONE      |Manifest: NOSIGNATURE
		Structory_1.20.2_v1.3.3.jar                       |Structory                     |structory                     |1.3.3               |DONE      |Manifest: NOSIGNATURE
		citadel-2.4.7-1.20.1.jar                          |Citadel                       |citadel                       |2.4.7               |DONE      |Manifest: NOSIGNATURE
		alexsmobs-1.22.6.jar                              |Alex's Mobs                   |alexsmobs                     |1.22.6              |DONE      |Manifest: NOSIGNATURE
		Nullscape_1.20.2_v1.2.3.jar                       |Nullscape                     |nullscape                     |1.2.3               |DONE      |Manifest: NOSIGNATURE
		Bookshelf-Forge-1.20.1-20.1.6.jar                 |Bookshelf                     |bookshelf                     |20.1.6              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		sophisticatedbackpacks-1.20.1-3.18.65.935.jar     |Sophisticated Backpacks       |sophisticatedbackpacks        |3.18.65.935         |DONE      |Manifest: NOSIGNATURE
		cfm-forge-1.20.1-7.0.0-pre36.jar                  |MrCrayfish's Furniture Mod    |cfm                           |7.0.0-pre36         |DONE      |Manifest: 0d:78:5f:44:c0:47:0c:8c:e2:63:a3:04:43:d4:12:7d:b0:7c:35:37:dc:40:b1:c1:98:ec:51:eb:3b:3c:45:99
		ferritecore-6.0.1-forge.jar                       |Ferrite Core                  |ferritecore                   |6.0.1               |DONE      |Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		balm-forge-1.20.1-7.1.4.jar                       |Balm                          |balm                          |7.1.4               |DONE      |Manifest: NOSIGNATURE
		arclight-1.20.1-1.0.0-053d747.jar                 |Arclight Mod                  |arclight                      |1.20.1-1.0.0-053d747|DONE      |Manifest: NOSIGNATURE
		Terralith_1.20.2_v2.4.7.jar                       |Terralith                     |terralith                     |2.4.7               |DONE      |Manifest: NOSIGNATURE
		forge-1.20.1-47.1.1-universal.jar                 |Forge                         |forge                         |47.1.1              |DONE      |Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
		silent-gear-1.20.1-3.5.1.jar                      |Silent Gear                   |silentgear                    |3.5.1               |DONE      |Manifest: NOSIGNATURE
		twilightforest-1.20.1-4.3.1860-universal.jar      |The Twilight Forest           |twilightforest                |4.3.1860            |DONE      |Manifest: NOSIGNATURE
		TF_Lost_Blocks-1.20.1-1.2.jar                     |Twilight Forest: The Lost Bloc|tflostblocks                  |1.20.1-1.2          |DONE      |Manifest: NOSIGNATURE
		ironchest-1.20.1-14.4.4.jar                       |Iron Chests                   |ironchest                     |1.20.1-14.4.4       |DONE      |Manifest: NOSIGNATURE
	Crash Report UUID: 802be0cb-da10-447a-a0b2-060e9b398468
	FML: 47.1
	Forge: net.minecraftforge:47.1.1
	Arclight Release: Trials
	Arclight: 
   Running: Arclight version arclight-1.20.1-1.0.0-053d747 (MC: 1.20.1) (Implementing API version 1.20.1-R0.1-SNAPSHOT) false
   Plugins: { nLogin v10.2.34 com.nickuc.login.loader.nLoginBukkitLoader [NickUC, Henry_Fabio, NullPointer_], SkinsRestorer v15.0.0 net.skinsrestorer.bukkit.SRBukkitBootstrap [knat, AlexProgrammerDE, Th3Tr0LLeR, McLive, DoNotSpamPls], GSit v1.5.0 dev.geco.gsit.GSitMain [Gecolay], FastAsyncWorldEdit v2.8.1 com.sk89q.worldedit.bukkit.WorldEditPlugin [Empire92, MattBDev, IronApollo, dordsor21, NotMyFault], Chunky v1.3.92 org.popcraft.chunky.ChunkyBukkit [pop4959], TabTPS v1.3.21 xyz.jpenilla.tabtps.spigot.TabTPSPlugin [jmp], DiscordSRV v1.26.2 github.scarsz.discordsrv.DiscordSRV [Scarsz, Androkai, Vankka], CoreProtect v22.2 net.coreprotect.CoreProtect [Intelli],}
   Warnings: DEFAULT
   Reload Count: 0
   Threads: { TIMED_WAITING DiscordSRV - JDA Gateway: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #4: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING bStats-Metrics: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING JNA Cleaner: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:176), MC-BOOTSTRAP/com.sun.jna@5.12.1/com.sun.jna.internal.Cleaner$1.run(Cleaner.java:58)], RUNNABLE Server thread: [TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer.m_207386_(DensityFunctions.java:270), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.DensityFunctions$Ap2.m_207386_(DensityFunctions.java:1132), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseChunk.m_198249_(NoiseChunk.java:260), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseChunk$$Lambda$17696/0x0000000802f8b360.get(Unknown Source), MC-BOOTSTRAP/it.unimi.dsi.fastutil@8.5.9/it.unimi.dsi.fastutil.longs.Long2IntOpenHashMap.computeIfAbsent(Long2IntOpenHashMap.java:489), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseChunk.m_198256_(NoiseChunk.java:250), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer.m_188447_(Aquifer.java:525), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer.m_188445_(Aquifer.java:501), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer.m_207104_(Aquifer.java:336), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseChunk.m_209215_(NoiseChunk.java:193), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseChunk$$Lambda$17667/0x0000000802f82f58.m_207387_(Unknown Source), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.material.MaterialRuleList.m_207387_(MaterialRuleList.java:15), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseChunk.m_209247_(NoiseChunk.java:225), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator.m_224239_(NoiseBasedChunkGenerator.java:216), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator.m_214096_(NoiseBasedChunkGenerator.java:125), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.chunk.ChunkGenerator.m_223235_(ChunkGeneratorMixin.java:579), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.structure.Structure.m_226585_(Structure.java:102), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure.m_214086_(BuriedTreasureStructure.java:21), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.structure.Structure.m_262864_(Structure.java:156), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.structure.StructureCheck.m_226755_(StructureCheck.java:105), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.structure.StructureCheck.m_226725_(StructureCheck.java:92), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.structure.StructureCheck$$Lambda$18898/0x00000008030fb8f0.get(Unknown Source), MC-BOOTSTRAP/it.unimi.dsi.fastutil@8.5.9/it.unimi.dsi.fastutil.longs.Long2BooleanOpenHashMap.computeIfAbsent(Long2BooleanOpenHashMap.java:449), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.levelgen.structure.StructureCheck.m_226729_(StructureCheck.java:91), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.StructureManager.m_220473_(StructureManager.java:165), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.chunk.ChunkGenerator.m_223198_(ChunkGeneratorMixin.java:248), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.chunk.ChunkGenerator.m_223188_(ChunkGeneratorMixin.java:235), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.chunk.ChunkGenerator.m_223037_(ChunkGeneratorMixin.java:175), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.level.ServerLevel.m_215011_(ServerLevelMixin.java:1129), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction.m_7372_(ExplorationMapFunction.java:76), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction.apply(LootItemConditionalFunction.java:31), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction.apply(LootItemConditionalFunction.java:20), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.functions.LootItemFunctions.m_80765_(LootItemFunctions.java:60), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.functions.LootItemFunctions$$Lambda$12840/0x00000008023ae008.apply(Unknown Source), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.functions.LootItemFunction.m_80728_(LootItemFunction.java:14), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.functions.LootItemFunction$$Lambda$16717/0x0000000802e4e438.accept(Unknown Source), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.entries.LootItem.m_6948_(LootItem.java:33), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1.m_6941_(LootPoolSingletonContainer.java:59), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.LootPool.m_79058_(LootPool.java:72), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.LootPool.m_79053_(LootPool.java:94), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.LootTable.m_79131_(LootTableMixin.java:85), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.LootTable.m_230922_(LootTableMixin.java:117), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.LootTable.eject$bhc000$arclight$nonPluginEvent(LootTableMixin.java:540), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.storage.loot.LootTable.m_287188_(LootTableMixin.java:139), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity.m_59640_(RandomizableContainerBlockEntity.java:82), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity.m_7208_(RandomizableContainerBlockEntity.java:154), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.level.ServerPlayer.m_5893_(ServerPlayerMixin.java:963), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.block.ChestBlock.m_6227_(ChestBlockMixin.java:236), TRANSFORMER/minecraft@1.20.1/net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase.m_60664_(BlockBehaviour_BlockStateBaseMixin.java:778), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.level.ServerPlayerGameMode.m_7179_(ServerPlayerGameModeMixin.java:846), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.network.ServerGamePacketListenerImpl.m_6371_(ServerPlayNetHandlerMixin.java:1055), TRANSFORMER/minecraft@1.20.1/net.minecraft.network.protocol.game.ServerboundUseItemOnPacket.m_5797_(CPlayerTryUseItemOnBlockPacketMixin.java:34), TRANSFORMER/minecraft@1.20.1/net.minecraft.network.protocol.game.ServerboundUseItemOnPacket.m_5797_(CPlayerTryUseItemOnBlockPacketMixin.java:8), TRANSFORMER/minecraft@1.20.1/net.minecraft.network.protocol.PacketUtils.mdc210f6$lambda$ensureRunningOnSameThread$0$0(PacketThreadUtilMixin.java:537), TRANSFORMER/minecraft@1.20.1/net.minecraft.network.protocol.PacketUtils$$Lambda$17251/0x0000000802ef5078.run(Unknown Source), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.TickTask.run(TickTask.java:18), TRANSFORMER/minecraft@1.20.1/net.minecraft.util.thread.BlockableEventLoop.m_6367_(BlockableEventLoop.java:156), TRANSFORMER/minecraft@1.20.1/net.minecraft.util.thread.ReentrantBlockableEventLoop.m_6367_(ReentrantBlockableEventLoop.java:23), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer.m_6367_(MinecraftServerMixin.java:770), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer.m_6367_(MinecraftServerMixin.java:161), TRANSFORMER/minecraft@1.20.1/net.minecraft.util.thread.BlockableEventLoop.m_7245_(BlockableEventLoop.java:130), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer.m_129961_(MinecraftServerMixin.java:753), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer.m_7245_(MinecraftServerMixin.java:747), TRANSFORMER/minecraft@1.20.1/net.minecraft.util.thread.BlockableEventLoop.m_18701_(BlockableEventLoop.java:139), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer.m_130012_(MinecraftServerMixin.java:733), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer.m_130011_(MinecraftServerMixin.java:2074), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer.m_206580_(MinecraftServerMixin.java:251), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.MinecraftServer$$Lambda$13337/0x000000080242b5f0.run(Unknown Source), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING JDA MainWS-WriteThread: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.Object.wait(Object.java:338), github.scarsz.discordsrv.dependencies.ws.client.WritingThread.waitForFrames(WritingThread.java:305), github.scarsz.discordsrv.dependencies.ws.client.WritingThread.main(WritingThread.java:89), github.scarsz.discordsrv.dependencies.ws.client.WritingThread.runMain(WritingThread.java:55), github.scarsz.discordsrv.dependencies.ws.client.WebSocketThread.run(WebSocketThread.java:45)], TIMED_WAITING WorldEdit Session Manager: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.util.TimerThread.mainLoop(Timer.java:563), java.base@18.0.2-ea/java.util.TimerThread.run(Timer.java:516)], RUNNABLE Notification Thread: [], RUNNABLE Server console handler: [java.base@18.0.2-ea/java.io.FileInputStream.read0(Native Method), java.base@18.0.2-ea/java.io.FileInputStream.read(FileInputStream.java:228), MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.terminal.impl.AbstractPty$PtyInputStream.read(AbstractPty.java:73), MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.utils.NonBlockingInputStream.read(NonBlockingInputStream.java:62), MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.utils.NonBlocking$NonBlockingInputStreamReader.read(NonBlocking.java:168), MC-BOOTSTRAP/jline.terminal@3.12.1/org.jline.utils.NonBlockingReader.read(NonBlockingReader.java:57), MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.keymap.BindingReader.readCharacter(BindingReader.java:133), MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.keymap.BindingReader.readBinding(BindingReader.java:110), MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.keymap.BindingReader.readBinding(BindingReader.java:61), MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.reader.impl.LineReaderImpl.doReadBinding(LineReaderImpl.java:848), MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.reader.impl.LineReaderImpl.readBinding(LineReaderImpl.java:868), MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.reader.impl.LineReaderImpl.readLine(LineReaderImpl.java:575), MC-BOOTSTRAP/jline.reader@3.12.1/org.jline.reader.impl.LineReaderImpl.readLine(LineReaderImpl.java:418), TRANSFORMER/forge@47.1.1/net.minecraftforge.server.console.TerminalHandler.handleCommands(TerminalHandler.java:46), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.dedicated.DedicatedServer$1.run(DedicatedServer.java:82)], WAITING DiscordSRV - JDA Rate Limit: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #3: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING arclight class cache saving thread: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #9: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING Worker-Main-5: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1724), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], RUNNABLE Netty Epoll Server IO #1: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait0(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:182), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWait(EpollEventLoop.java:302), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:366), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #6: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Reference Handler: [java.base@18.0.2-ea/java.lang.ref.Reference.waitForReferencePendingList(Native Method), java.base@18.0.2-ea/java.lang.ref.Reference.processPendingReferences(Reference.java:253), java.base@18.0.2-ea/java.lang.ref.Reference$ReferenceHandler.run(Reference.java:215)], TIMED_WAITING DiscordSRV - Nickname Updater: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), github.scarsz.discordsrv.objects.threads.NicknameUpdater.run(NicknameUpdater.java:104)], TIMED_WAITING ForkJoinPool.commonPool-worker-36: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], TIMED_WAITING IO-Worker-39: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #2: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING OkHttp ConnectionPool: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.Object.wait(Object.java:472), github.scarsz.discordsrv.dependencies.okhttp3.ConnectionPool.lambda$new$0(ConnectionPool.java:66), github.scarsz.discordsrv.dependencies.okhttp3.ConnectionPool$$Lambda$15722/0x0000000802c62f30.run(Unknown Source), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1136), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING Thread-28: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), net.coreprotect.thread.NetworkHandler.run(NetworkHandler.java:360), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING pool-13-thread-2: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING process reaper: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #0: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING bStats-Metrics: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING Spigot Metrics Thread: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.util.TimerThread.mainLoop(Timer.java:563), java.base@18.0.2-ea/java.util.TimerThread.run(Timer.java:516)], TIMED_WAITING IO-Worker-36: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING DiscordSRV - JDA Rate Limit: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING pool-14-thread-1: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING Timer hack thread: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), TRANSFORMER/minecraft@1.20.1/net.minecraft.Util$9.run(Util.java:672)], TIMED_WAITING pool-16-thread-1: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING ForkJoinPool.commonPool-worker-37: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], TIMED_WAITING Common-Cleaner: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155), java.base@18.0.2-ea/jdk.internal.ref.CleanerImpl.run(CleanerImpl.java:140), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833), java.base@18.0.2-ea/jdk.internal.misc.InnocuousThread.run(InnocuousThread.java:162)], TIMED_WAITING Yggdrasil Key Fetcher: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING Thread-1: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:376), MC-BOOTSTRAP/com.electronwill.nightconfig.core@3.6.4/com.electronwill.nightconfig.core.file.FileWatcher$WatcherThread.run(FileWatcher.java:190)], TIMED_WAITING ForkJoinPool.commonPool-worker-39: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], TIMED_WAITING DiscordSRV - JDA Rate Limit: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING bStats-Metrics: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #8: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING Worker-Main-1: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1724), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], TIMED_WAITING DiscordSRV - Presence Updater: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), github.scarsz.discordsrv.objects.threads.PresenceUpdater.run(PresenceUpdater.java:117)], RUNNABLE FileSystemWatchService: [java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService.poll(Native Method), java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService$Poller.run(LinuxWatchService.java:314), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #5: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE FileSystemWatchService: [java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService.poll(Native Method), java.base@18.0.2-ea/sun.nio.fs.LinuxWatchService$Poller.run(LinuxWatchService.java:314), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING DiscordSRV - JDA Callback 0: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], TIMED_WAITING ForkJoinPool.commonPool-worker-40: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], TIMED_WAITING bStats-Metrics: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING IO-Worker-34: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue$TransferStack.transfer(SynchronousQueue.java:401), java.base@18.0.2-ea/java.util.concurrent.SynchronousQueue.poll(SynchronousQueue.java:903), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1061), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING Java2D Disposer: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:176), java.desktop@18.0.2-ea/sun.java2d.Disposer.run(Disposer.java:145), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING DiscordSRV - Server Watchdog: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), github.scarsz.discordsrv.objects.threads.ServerWatchdog.run(ServerWatchdog.java:63)], TIMED_WAITING Thread-11: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), net.coreprotect.consumer.Consumer.run(Consumer.java:131), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #10: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING Finalizer: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:176), java.base@18.0.2-ea/java.lang.ref.Finalizer$FinalizerThread.run(Finalizer.java:183)], TIMED_WAITING DiscordSRV - Channel Updater: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), github.scarsz.discordsrv.objects.threads.ChannelUpdater.run(ChannelUpdater.java:93)], TIMED_WAITING bStats-Metrics: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING Log4j2-AsyncAppenderEventDispatcher-1-Async: [java.base@18.0.2-ea/java.util.concurrent.LinkedBlockingQueue.offer(LinkedBlockingQueue.java:416), java.base@18.0.2-ea/java.util.AbstractQueue.add(AbstractQueue.java:95), MC-BOOTSTRAP/logging@1.1.1/com.mojang.logging.plugins.QueueLogAppender.append(QueueLogAppender.java:34), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.config.AppenderControl.tryCallAppender(AppenderControl.java:161), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.config.AppenderControl.callAppender0(AppenderControl.java:134), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.config.AppenderControl.callAppenderPreventRecursion(AppenderControl.java:125), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.config.AppenderControl.callAppender(AppenderControl.java:89), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.appender.AsyncAppenderEventDispatcher.dispatch(AsyncAppenderEventDispatcher.java:130), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.appender.AsyncAppenderEventDispatcher.dispatchAll(AsyncAppenderEventDispatcher.java:92), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.appender.AsyncAppenderEventDispatcher.run(AsyncAppenderEventDispatcher.java:74)], RUNNABLE DestroyJavaVM: [], TIMED_WAITING DiscordSRV ExpiryThread: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), github.scarsz.discordsrv.objects.ExpiringDualHashBidiMap$ExpiryThread.run(ExpiringDualHashBidiMap.java:132)], TIMED_WAITING bStats-Metrics: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING Worker-Main-4: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], TIMED_WAITING DiscordSRV - JDA Rate Limit: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Server Watchdog: [java.base@18.0.2-ea/java.lang.Thread.dumpThreads(Native Method), java.base@18.0.2-ea/java.lang.Thread.getAllStackTraces(Thread.java:1662), TRANSFORMER/arclight@1.20.1-1.0.0-053d747/org.bukkit.craftbukkit.v1_20_R1.CraftCrashReport.get(CraftCrashReport.java:33), TRANSFORMER/arclight@1.20.1-1.0.0-053d747/org.bukkit.craftbukkit.v1_20_R1.CraftCrashReport.get(CraftCrashReport.java:1), LAYER PLUGIN/fmlcore@1.20.1-47.1.1/net.minecraftforge.fml.CrashReportCallables$1.get(CrashReportCallables.java:49), LAYER PLUGIN/fmlcore@1.20.1-47.1.1/net.minecraftforge.fml.CrashReportCallables$1.get(CrashReportCallables.java:39), TRANSFORMER/minecraft@1.20.1/net.minecraft.SystemReport.m_143522_(SystemReport.java:66), TRANSFORMER/forge@47.1.1/net.minecraftforge.logging.CrashReportExtender.extendSystemReport(CrashReportExtender.java:33), TRANSFORMER/minecraft@1.20.1/net.minecraft.CrashReport.m_127519_(CrashReport.java:69), TRANSFORMER/minecraft@1.20.1/net.minecraft.CrashReport.m_127526_(CrashReport.java:113), TRANSFORMER/minecraft@1.20.1/net.minecraft.CrashReport.m_127512_(CrashReport.java:134), TRANSFORMER/minecraft@1.20.1/net.minecraft.server.dedicated.ServerWatchdog.run(ServerWatchdog.java:69), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE JDA MainWS-ReadThread: [java.base@18.0.2-ea/sun.nio.ch.Net.poll(Native Method), java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.park(NioSocketImpl.java:178), java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.timedRead(NioSocketImpl.java:282), java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.implRead(NioSocketImpl.java:306), java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl.read(NioSocketImpl.java:347), java.base@18.0.2-ea/sun.nio.ch.NioSocketImpl$1.read(NioSocketImpl.java:800), java.base@18.0.2-ea/java.net.Socket$SocketInputStream.read(Socket.java:966), java.base@18.0.2-ea/sun.security.ssl.SSLSocketInputRecord.read(SSLSocketInputRecord.java:478), java.base@18.0.2-ea/sun.security.ssl.SSLSocketInputRecord.readHeader(SSLSocketInputRecord.java:472), java.base@18.0.2-ea/sun.security.ssl.SSLSocketInputRecord.bytesInCompletePacket(SSLSocketInputRecord.java:70), java.base@18.0.2-ea/sun.security.ssl.SSLSocketImpl.readApplicationRecord(SSLSocketImpl.java:1460), java.base@18.0.2-ea/sun.security.ssl.SSLSocketImpl$AppInputStream.read(SSLSocketImpl.java:1064), java.base@18.0.2-ea/java.io.BufferedInputStream.fill(BufferedInputStream.java:244), java.base@18.0.2-ea/java.io.BufferedInputStream.read1(BufferedInputStream.java:284), java.base@18.0.2-ea/java.io.BufferedInputStream.read(BufferedInputStream.java:343), java.base@18.0.2-ea/java.io.FilterInputStream.read(FilterInputStream.java:133), github.scarsz.discordsrv.dependencies.ws.client.WebSocketInputStream.readBytes(WebSocketInputStream.java:165), github.scarsz.discordsrv.dependencies.ws.client.WebSocketInputStream.readFrame(WebSocketInputStream.java:46), github.scarsz.discordsrv.dependencies.ws.client.ReadingThread.readFrame(ReadingThread.java:338), github.scarsz.discordsrv.dependencies.ws.client.ReadingThread.main(ReadingThread.java:99), github.scarsz.discordsrv.dependencies.ws.client.ReadingThread.runMain(ReadingThread.java:64), github.scarsz.discordsrv.dependencies.ws.client.WebSocketThread.run(WebSocketThread.java:45)], TIMED_WAITING ForkJoinPool.commonPool-worker-38: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkUntil(LockSupport.java:410), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1726), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], WAITING Log4j2-AsyncAppenderEventDispatcher-2-Async: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.ArrayBlockingQueue.take(ArrayBlockingQueue.java:420), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.appender.AsyncAppenderEventDispatcher.dispatchAll(AsyncAppenderEventDispatcher.java:82), MC-BOOTSTRAP/org.apache.logging.log4j.core@2.19.0/org.apache.logging.log4j.core.appender.AsyncAppenderEventDispatcher.run(AsyncAppenderEventDispatcher.java:74)], TIMED_WAITING Okio Watchdog: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.Object.wait(Object.java:472), github.scarsz.discordsrv.dependencies.okio.AsyncTimeout.awaitTimeout(AsyncTimeout.java:362), github.scarsz.discordsrv.dependencies.okio.AsyncTimeout$Watchdog.run(AsyncTimeout.java:313)], TIMED_WAITING mysql-cj-abandoned-connection-cleanup: [java.base@18.0.2-ea/java.lang.Object.wait(Native Method), java.base@18.0.2-ea/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:155), MC-BOOTSTRAP/mysql.connector.j@8.0.33/com.mysql.cj.jdbc.AbandonedConnectionCleanupThread.run(AbandonedConnectionCleanupThread.java:91), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1136), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING pool-19-thread-1: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Netty Epoll Server IO #11: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait0(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:182), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWait(EpollEventLoop.java:302), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:366), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING Thread-10: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), net.coreprotect.thread.CacheHandler.run(CacheHandler.java:30), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING fawe-clipboard-0: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.LinkedBlockingQueue.take(LinkedBlockingQueue.java:435), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING bStats-Metrics: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], RUNNABLE Signal Dispatcher: [], TIMED_WAITING DiscordSRV - Channel Topic Updater: [java.base@18.0.2-ea/java.lang.Thread.sleep(Native Method), github.scarsz.discordsrv.objects.threads.ChannelTopicUpdater.run(ChannelTopicUpdater.java:54)], WAITING pool-13-thread-4: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING Worker-Main-3: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.awaitWork(ForkJoinPool.java:1724), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1623), java.base@18.0.2-ea/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)], RUNNABLE Netty Epoll Server IO #7: [MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native Method), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:209), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.Native.epollWait(Native.java:202), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.epollWaitNoTimerChange(EpollEventLoop.java:306), MC-BOOTSTRAP/io.netty.transport.classes.epoll@4.1.82.Final/io.netty.channel.epoll.EpollEventLoop.run(EpollEventLoop.java:363), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997), MC-BOOTSTRAP/io.netty.common@4.1.82.Final/io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], TIMED_WAITING pool-13-thread-1: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.parkNanos(LockSupport.java:252), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.awaitNanos(AbstractQueuedSynchronizer.java:1672), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1182), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING pool-13-thread-3: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)], WAITING DiscordSRV - JDA Rate Limit: [java.base@18.0.2-ea/jdk.internal.misc.Unsafe.park(Native Method), java.base@18.0.2-ea/java.util.concurrent.locks.LockSupport.park(LockSupport.java:341), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode.block(AbstractQueuedSynchronizer.java:506), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.unmanagedBlock(ForkJoinPool.java:3464), java.base@18.0.2-ea/java.util.concurrent.ForkJoinPool.managedBlock(ForkJoinPool.java:3435), java.base@18.0.2-ea/java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject.await(AbstractQueuedSynchronizer.java:1623), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:1177), java.base@18.0.2-ea/java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue.take(ScheduledThreadPoolExecutor.java:899), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1062), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1122), java.base@18.0.2-ea/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635), java.base@18.0.2-ea/java.lang.Thread.run(Thread.java:833)],}
   Recent tasks from 69591-69621{DiscordSRV:github.scarsz.discordsrv.listeners.PlayerAdvancementDoneListener$$Lambda$17977/0x0000000802fc3c08@69624,nLogin:com.nickuc.login.tasks.LoginMainQueueTask@69624,nLogin:com.nickuc.login.ΩιθλξαψυθΔΔρνξτ$$Lambda$14298/0x00000008025fe838@69629,nLogin:com.nickuc.login.tasks.LoginMainQueueTask@69629,SkinsRestorer:net.skinsrestorer.shared.plugin.SRPlugin$$Lambda$14560/0x0000000802a0e4b0@69629,nLogin:com.nickuc.login.ΛνμθΦΛψοφρτδςνη$$Lambda$14305/0x0000000802909328@69631,nLogin:com.nickuc.login.ωΓχοΦνμφνγ$$Lambda$14345/0x000000080294a648@69631,nLogin:com.nickuc.login.tasks.LoginMainQueueTask@69634,nLogin:com.nickuc.login.tasks.LoginMainQueueTask@69639,DiscordSRV:github.scarsz.discordsrv.listeners.PlayerAdvancementDoneListener$$Lambda$17977/0x0000000802fc3c08@69644,nLogin:com.nickuc.login.tasks.LoginMainQueueTask@69644,DiscordSRV:github.scarsz.discordsrv.listeners.PlayerAdvancementDoneListener$$Lambda$17977/0x0000000802fc3c08@69646,nLogin:com.nickuc.login.ΩιθλξαψυθΔΔρνξτ$$Lambda$14298/0x00000008025fe838@69649,nLogin:com.nickuc.login.tasks.LoginMainQueueTask@69649,nLogin:com.nickuc.login.ωΓχοΦνμφνγ$$Lambda$14345/0x000000080294a648@69651,}
   Force Loaded Chunks: { world: {}, world/twilightforest/twilight_forest: {}, world/DIM-1: {}, world/DIM1: {},}

   

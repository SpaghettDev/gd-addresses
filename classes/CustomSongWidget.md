This is the widget that appears at the bottom center of a LevelInfoLayer and in the LevelSettingsLayer.

Here are the known addresses:
```cpp
void __thiscall CustomSongWidget::~CustomSongWidget(CustomSongWidget* this, byte p0) = base + 0x683f0;

bool __thiscall CustomSongWidget::init(CustomSongWidget* this, SongInfoObject* songInfo, LevelSettingsObject* levelSettings, bool hasDefaultSong, bool hideBackground) = base + 0x685b0;

void __thiscall CustomSongWidget::loadSongInfoFinished(CustomSongWidget* this, SongInfoObject* songInfo) = base + 0x6a1e0;

void __thiscall CustomSongWidget::downloadSongFinished(CustomSongWidget* this, SongInfoObject* song) = base + 0x6a2c0;

void __thiscall CustomSongWidget::downloadSongFailed(int param_1, GJSongError) = base + 0x6A260;

void __thiscall CustomSongWidget::changeStateText(CustomSongWidget* this, int state) = base + 0x6a340;

void __thiscall CustomSongWidget::songStateChanged(CustomSongWidget* this) = base + 0x69bd0;

void __thiscall CustomSongWidget::FLAlert_Clicked(CustomSongWidget* this, FLAlertLayer* p1, bool p2) = base + 0x6a3f0;

void __thiscall CustomSongWidget::onStateChange(CustomSongWidget* this, int songID, int state) = base + 0x6a260;

bool __thiscall CustomSongWidget::onMore(CustomSongWidget* this, SongInfoObject* songInfo) = base + 0x250a80;

void __thiscall CustomSongWidget::onPlaySongButton(CustomSongWidget* this) = base + 0x69970;

void __thiscall CustomSongWidget::updateSongInfo(CustomSongWidget* this, SongInfoObject* songInfo) = base + 0x69280;

void __thiscall CustomSongWidget::updateProgressBar(int p1) = base + 0x69B40;

void __thiscall CustomSongWidget::updateError(GJSongError p1) = base + 0x6A340;
```

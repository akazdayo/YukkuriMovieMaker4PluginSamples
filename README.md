# �������MovieMaker4 �v���O�C���T���v���W
## �v���W�F�N�g�̍쐬���@
.NET7�p�̃N���X���C�u�����v���W�F�N�g���쐬���Ă��������B  
### �v���W�F�N�g�̐ݒ�
�v���W�F�N�g�̍쐬��A�v���W�F�N�g�t�@�C����`<TargetFramework>`��`net7.0-windows10.0.19041.0`�ɕύX���A���̉���`<UseWPF>true</UseWPF>`��ǉ����Ă��������B
```xml
<PropertyGroup>
    <TargetFramework>net7.0-windows10.0.19041.0</TargetFramework>
    <UseWPF>true</UseWPF>

    ...�ȗ�...

</PropertyGroup>
```
### �Q�Ƃ̒ǉ�
1. �\�����[�V�����G�N�X�v���[���[����`�ˑ��֌W`���E�N���b�N���A`�v���W�F�N�g�Q�Ƃ̒ǉ�(R)`���N���b�N���܂��B
1. �Q�ƃ}�l�[�W���[�E�B���h�E������`�Q��(B)`�{�^�����N���b�N���܂��B
1. YMM4���C���X�g�[�����Ă���t�H���_���ɂ���`YukkuriMovieMaker.Plugin.dll`��`YukkuriMovieMaker.Controls.dll`��I�����A`OK`�{�^�����N���b�N���܂��B
1. `OK`�{�^�����N���b�N���A�Q�ƃ}�l�[�W���[����܂��B
1. �v���O�C���̎�������`CS0012: �^'T' �́A�Q�Ƃ���Ă��Ȃ��A�Z���u���ɒ�`����Ă��܂��B�A�Z���u�� '�A�Z���u����, Version=x.x.x.x, Culture=xxx, PublicKeyToken=xxx' �ɎQ�Ƃ�ǉ�����K�v������܂��B`�ƃG���[���\�����ꂽ�ꍇ�A�K�v�ɉ�����YMM4�t�H���_���ɂ���`�A�Z���u����.dll`���Q�Ƃɒǉ����Ă��������B
## �v���O�C���̓ǂݍ���
�r���h��A`YMM4�t�H���_\user\plugin\`�t�H���_����`�v���O�C�����t�H���_`���쐬���A`�v���O�C����.dll`��ۑ����Ă��������B  
YMM4�t�H���_���ɑ��݂��Ȃ�dll��ǂݍ���ł���ꍇ�A����dll���ꏏ�ɃR�s�[���Ă��������B  

�v���O�C��������ɓǂݍ��܂ꂽ�ꍇ�AYMM4��`�ݒ�`��`�v���O�C��`��`�v���O�C���ꗗ`�Ƀv���O�C�������\������܂��B

## �T���v���ꗗ
### �����ǂݍ��݃v���O�C��
- [SampleAusioSourcePlugin](./SampleSourcePlugin/README.md)

### �f���ǂݍ��݃v���O�C��
- [SampleVideoSourcePlugin](./SampleVideoSourcePlugin/README.md)

### �摜�ǂݍ��݃v���O�C��
- [SampleWICImageSourcePlugin](./SampleWICImageSourcePlugin/README.md)

### �����G�ǂݍ��݃v���O�C��
- [SampleTachiePlugin](./SampleTachiePlugin/README.md)

### ���揑���o���v���O�C��
- [SampleVideoWriterPlugin](./SampleVideoWriterPlugin/README.md)

### �����G�t�F�N�g
- [SampleAudioEffect](./SampleAudioEffect/README.md)

### �f���G�t�F�N�g
- [SampleVideoEffects](./SampleVideoEffects/README.md)

### ���������v���O�C��
- [SampleSAPI5VoicePlugin](./SampleSAPI5VoicePlugin/README.md)

### AI�e�L�X�g�⊮�v���O�C��
- [SampleTextCompletionPlugin](./SampleTextCompletionPlugin/README.md)

### �����ꉻ�v���O�C��
- [SampleLocalizePlugin](./SampleLocalizePlugin/README.md)


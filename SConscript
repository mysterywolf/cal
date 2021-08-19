Import('rtconfig')
from building import *

src	= Glob('*.c')
group = DefineGroup('cal', src, depend = ['PKG_USING_CAL'])
Return('group')

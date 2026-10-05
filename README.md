<img width="1024" height="583" alt="gongneng" src="https://github.com/user-attachments/assets/c873ba44-d624-4b6b-8c00-4aab175b5d07" />
<p>
    <span style="text-wrap-mode: nowrap;">⚙ 自定义桌宠形象配置文件 config.json (exe同目录)</span>
</p>
<p>
    <span style="text-wrap-mode: nowrap;">{</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>&quot;📄 配置说明：screen&quot;: &quot;随机移动桌面屏幕范围：false（默认不超出桌面范围） true（只超出桌宠当前窗口大小）&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>&quot;screen&quot;:false,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>&quot;📄 配置说明：待机动作数组&quot;: &quot;待机状态下随机执行动作；3000=3秒随机执行 (move = 随机执行 move 内数组动作)&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>&quot;idle&quot;:[&quot;idle&quot;,&quot;move&quot;,&quot;飞行&quot;,&quot;攻击&quot;,3000],</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>&quot;📄 配置说明：移动随机数组&quot;: &quot;动作名称 = 移动速度（倍率：5 = 100x5=500px像素）&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>&quot;move&quot;:[</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>{&quot;飞行&quot;:5}</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>],</span>
</p>
<p>
    <span style="text-wrap-mode: nowrap;">&nbsp; &quot;📄 配置说明：&quot;:&quot;创建动画数组&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>&quot;animat&quot;:{</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>&quot;📄 配置说明：&quot;:&quot;定义的动作名称（随意填写）&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>&quot;idle&quot;:{</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;📄 配置说明：loop=true &quot;:&quot;循环动作&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;loop&quot;:true,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;📄 配置说明：180&quot;:&quot;每帧执行间隔（image时间自定义无效）&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;average&quot;:180,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;📄 配置说明：动作图片数组&quot;:&quot;可参考攻击动作&gt;指定帧时间&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;image&quot;:[</span>
</p>
<p>
    <span style="text-wrap-mode: nowrap;">&nbsp; &nbsp; &nbsp; &nbsp; &quot;📄 配置说明：帧图片地址 默认同目录（可指定真实路径 例如: d:\zhuochong\人物.png）&quot;</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;天使 8K.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>]</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>},</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>&quot;飞行&quot;:{</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;📄 配置说明&quot;:&quot;飞行动作&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;loop&quot;: true,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;average&quot;:125,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;image&quot;:[</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;飞行/01.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;飞行/02.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;飞行/03.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;飞行/04.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;飞行/05.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;飞行/06.png&quot;</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>]</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>},</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>&quot;攻击&quot;:{</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;📄 配置说明&quot;:&quot;攻击动作（自定义帧时间格式）&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>&quot;image&quot;:{</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;000&quot;:&quot;攻击/0.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;125&quot;:&quot;攻击/1.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;250&quot;:&quot;攻击/2.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;375&quot;:&quot;攻击/3.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;500&quot;:&quot;攻击/4.png&quot;,</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">				</span>&quot;625&quot;:&quot;攻击/5.png&quot;</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">			</span>}</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">		</span>}</span>
</p>
<p>
    <span style="white-space-collapse: collapse;"><span style="white-space:pre">	</span>}</span>
</p>
<p>
    <span style="text-wrap-mode: nowrap;">}</span>
</p>
<p>
    <br/>
</p>

请转写对白，识别说话人并提供时间戳。若输入为视频，结合画面分析说话人与声音的对应关系；若仅为音频，只依据声音区分说话人。使用稳定的 speakerX 编号，不猜测真实身份。听不清时标明，不补写台词。中文说明，实际对白保留原文。
严格使用以下输出格式（保留标记）：
<soc><sos><start_time>对白原文<end_time><speakerX><eos>...<eoc>
将 start_time 和 end_time 替换为以媒体开头为零点的秒数，将 speakerX 替换为 speaker1、speaker2 等。不要把示例占位文字当作实际内容。无可辨对白时输出 <soc><eoc>。

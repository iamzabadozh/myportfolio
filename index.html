import React, { useState, useEffect } from 'react';
import { motion, AnimatePresence } from 'framer-motion';
import { Menu, X, Download, Github, Linkedin, Mail, Phone, ExternalLink, ChevronDown, ArrowRight } from 'lucide-react';

const Portfolio = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [scrollProgress, setScrollProgress] = useState(0);
  const [activeSection, setActiveSection] = useState('home');
  const [isDarkMode, setIsDarkMode] = useState(true);
  const [isLoading, setIsLoading] = useState(true);

  // Profile image - base64 encoded to work without external files
  const profileImageUrl = 'data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEA3ADcAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCAH6AP8DASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwD3qiiigAooooAKKKKACiiigAooooAKKKKACiiigAooqG4u7e1TfcTxwr6yOFH60ATUVz15438O2LMkupRF1xxHl8/TFXLLxJo9/Gj2+oQHecBWba2foeaANWis0a/pRuDb/bYhMAT5ZOG/Kr0c8Uoykit9DQBJRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUUUAFFFFABRRRQAUUVyGt+Obaz8yCwUTTLwZG4RfX3NCVwOlvNSsrBQbu5ihz0DNyfwrJbxpoSSlGu8AfxlDtP0ryjUtWvNUuHlbt1dhzjv9KpXFza2y7p51DjqznoPrWigK560/j/AEZcEtIqf32Xj9M5rGu/iRIxkFpY7VA4eRv16V5PLrc9yxj06zBUHH2i4+VfwHU003FwVKXFzLKx+9sO0H6AcgVSpolyO6n+JGs+ZlXWMAnCmMDPpyf8K5LWNc1HUrgm9uS4LFhuOQM/SsqSa0hUiFFQ5y2P8c5qlPe2/wB5pge+DJj+lVyInmZckunZSok2jHVeMis9iwGY7icnPZqat/DLwmxjjjA3Glb7YSfKiYH1CKP6U+UOYnK3QBlE04XBIODmM/4Uum6hr1lcB7XVXVicjc/BP4/1qot5qVspHlu6t/tDmpk1F1GTCyy90YZBHtg1lNFo7yy+MGsaBG1vq1r9slLZ8x22kD2xXeeGfix4e18pDLN9jumwAkv3Wb0B/wAa8Hmv1uyPMj2g8ODwf1x/Wqb2U6FpbWZxhsBGHX6HgGsdUWfXscqyoGU8Gn14R8KfF81lqn9lalMximOIzI3KN6c9c17uDkVQgooooAKKKa5IAA6k4FAAzqvBPPpQJFJxnn0IxT0QIOOvc+tKyhhhhkUANopq5DFCc46H2p1ABRRRQAUUUUAFFFFABTXdY0Z2OFUZJ9qdXmni3xzcTNLpui7CuGjnlZTkdsL6d+aaVwE8WeOGeeSx0+V0QD5nUENnuDXnjzqT5kjO+5sqgGc+/vU6weXEVj2yzcmQsflH+8fQVVnvLe1iILB3fq7LgH/dXqfx/WtoxsS2QuL+6Uu8qQ246bz/ACA61WuI7S1UNL++kHPm3B4+oWoHvby9n8u3GGHG5hucD6cBfxI+lLDpNuZDJdeZdyj+E8gH0J+6KuxDZEdTikxHBG1w56YXCqPbFSNbT3EbPcOsESdj/wDW6/pWg8ckIVHmS3Q9Y4FzgfXoKpyGPd+4tSxU/LJMx/P/APVVWFcqxR24VgE84g9Qwx/iP1pXS43bRYSqh6MBwfyFJLc6htIW6t4AT1VMn+dUWkuo3JbVJWJ64gH+FLYC2TMfl2tnP8RJ/wDZqjlhmZf3ksZXqTs6frUH20KMyTXEmOp8sj/2WoxqVrkn7RKGxwHH/wCqhtAkBB3/ACfZ3x/dO0/4VIbWeSMlCQM4w75/x/pUH26F2x8pbuWBH9Ka19Cu4MAPQrz/ACP9Kykuidmu4YlEmWgHG8rtA/HkfnVS6l2sDHKEfHMeRg/Qjj+VWbfURIV8m8KkdVcD+XQ/lRdkXkeZILa4fqWtyEkH4DGfyrFo0RXsZrl7gKpxL/CQwz9Pxr6Q+Gvi2XxJoUaXKsbm3UJJIWB3eh/Kvl+QLE6vE0qFWyN3Y/0rrPC2tT2WpiRJChLBsrwPWkDPqyiuW8J+Lk8QNJbyqsdwi7wFPDL/APW/rXU0xBTX4ZG7Buf5U6kIBGD0oAr3dgLuRXNzdRYGMQylQaZb6YLedZReXkm3+GSYsp+oq0C6cD5h7nmgtI3AAX3JzU8qvcv2kkuW+n9eQZzMx9ABTqRVCjApaogKKKKACiiigAoorjPGXihbOzks7Ro3kmDRE5OVPc/Qfz49aLXAoeMvGqr5uk6azebnbLMDjaO4H+NcDGY40Z1YHP35Sep9B6/WqEiMykM22MOZHHV/9kH+ZpJXEUKTXCMwY7ba0QcyHtkdhW0Y2JbIrzUFS1LEiCzU4BxzI3t6n/PFZ1rpsmoubu4Y28BOF3n5j/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPFp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPHp6dtxDSn+g/AVRm1GFWKWazSM3LzHG4/8AX9uv0rcj02NJBeagwnuwvCk4ihX0Ht796rXN+8wZ7ZlhiUYNy4xgeka9vrWhArfZdNhW3AaNSM7SMu/4dvxrputRljQAPH';

  useEffect(() => {
    setTimeout(() => setIsLoading(false), 1500);
  }, []);

  useEffect(() => {
    const handleScroll = () => {
      const scrollTop = window.scrollY;
      const docHeight = document.documentElement.scrollHeight - window.innerHeight;
      const scrollPercent = (scrollTop / docHeight) * 100;
      setScrollProgress(scrollPercent);
    };

    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  // Loading Animation
  if (isLoading) {
    return (
      <motion.div 
        className="fixed inset-0 bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900 flex items-center justify-center z-50"
        exit={{ opacity: 0 }}
        transition={{ duration: 0.5 }}
      >
        <div className="flex flex-col items-center gap-4">
          <motion.div 
            className="relative w-16 h-16"
            animate={{ rotate: 360 }}
            transition={{ duration: 2, repeat: Infinity }}
          >
            <div className="absolute inset-0 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full blur-lg opacity-75"></div>
            <div className="absolute inset-2 bg-slate-900 rounded-full"></div>
            <motion.div 
              className="absolute inset-0 border-2 border-transparent border-t-purple-500 border-r-pink-500 rounded-full"
              animate={{ rotate: -360 }}
              transition={{ duration: 1.5, repeat: Infinity }}
            ></motion.div>
          </motion.div>
          <motion.p 
            className="text-white text-sm font-light tracking-widest"
            animate={{ opacity: [0.5, 1, 0.5] }}
            transition={{ duration: 1.5, repeat: Infinity }}
          >
            Loading Portfolio
          </motion.p>
        </div>
      </motion.div>
    );
  }

  // Navigation
  const NavBar = () => (
    <motion.nav 
      className={`fixed w-full top-0 z-40 backdrop-blur-md border-b border-purple-500/10 transition-all duration-300 ${isDarkMode ? 'bg-slate-900/80' : 'bg-white/80'}`}
      initial={{ y: -100 }}
      animate={{ y: 0 }}
      transition={{ duration: 0.8, delay: 0.2 }}
    >
      <div className="absolute top-0 left-0 right-0 h-1 bg-gradient-to-r from-purple-500 via-pink-500 to-purple-500" style={{ width: `${scrollProgress}%` }}></div>
      
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
        <div className="flex items-center justify-between">
          <motion.div 
            className="flex items-center gap-2"
            whileHover={{ scale: 1.05 }}
          >
            <div className="w-10 h-10 bg-gradient-to-br from-purple-500 to-pink-500 rounded-full flex items-center justify-center">
              <span className="text-white font-bold text-lg">RA</span>
            </div>
            <span className={`font-bold text-xl bg-gradient-to-r from-purple-400 to-pink-400 bg-clip-text text-transparent`}>
              Rissa Anne
            </span>
          </motion.div>

          {/* Desktop Menu */}
          <div className="hidden md:flex items-center gap-8">
            {['About', 'Skills', 'Experience', 'Projects', 'Services', 'Contact'].map((item, idx) => (
              <motion.a
                key={item}
                href={`#${item.toLowerCase()}`}
                className={`text-sm font-medium transition-colors relative group ${isDarkMode ? 'text-gray-300 hover:text-purple-400' : 'text-gray-700 hover:text-purple-600'}`}
                whileHover={{ scale: 1.1 }}
                initial={{ opacity: 0, y: -10 }}
                animate={{ opacity: 1, y: 0 }}
                transition={{ delay: 0.1 + idx * 0.05 }}
              >
                {item}
                <span className="absolute bottom-0 left-0 w-0 h-0.5 bg-gradient-to-r from-purple-500 to-pink-500 group-hover:w-full transition-all duration-300"></span>
              </motion.a>
            ))}
          </div>

          {/* Right Side Icons */}
          <div className="flex items-center gap-4">
            <motion.button
              onClick={() => setIsDarkMode(!isDarkMode)}
              className={`p-2 rounded-lg ${isDarkMode ? 'bg-purple-500/20' : 'bg-purple-100'}`}
              whileHover={{ scale: 1.1 }}
              whileTap={{ scale: 0.95 }}
            >
              {isDarkMode ? '🌙' : '☀️'}
            </motion.button>
            
            <motion.button
              className="hidden md:inline-flex px-4 py-2 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-lg font-medium text-sm hover:shadow-lg hover:shadow-purple-500/50 transition-all"
              whileHover={{ scale: 1.05 }}
              whileTap={{ scale: 0.95 }}
            >
              <Download className="w-4 h-4 mr-2" />
              Resume
            </motion.button>

            {/* Mobile Menu Toggle */}
            <motion.button
              className="md:hidden p-2"
              onClick={() => setIsMenuOpen(!isMenuOpen)}
              whileTap={{ scale: 0.95 }}
            >
              {isMenuOpen ? <X className="w-6 h-6" /> : <Menu className="w-6 h-6" />}
            </motion.button>
          </div>
        </div>

        {/* Mobile Menu */}
        <AnimatePresence>
          {isMenuOpen && (
            <motion.div
              initial={{ opacity: 0, height: 0 }}
              animate={{ opacity: 1, height: 'auto' }}
              exit={{ opacity: 0, height: 0 }}
              className="md:hidden mt-4 pb-4 border-t border-purple-500/20"
            >
              {['About', 'Skills', 'Experience', 'Projects', 'Services', 'Contact'].map((item) => (
                <motion.a
                  key={item}
                  href={`#${item.toLowerCase()}`}
                  className={`block py-2 font-medium transition-colors ${isDarkMode ? 'text-gray-300 hover:text-purple-400' : 'text-gray-700 hover:text-purple-600'}`}
                  whileHover={{ x: 10 }}
                  onClick={() => setIsMenuOpen(false)}
                >
                  {item}
                </motion.a>
              ))}
            </motion.div>
          )}
        </AnimatePresence>
      </div>
    </motion.nav>
  );

  // Hero Section
  const HeroSection = () => (
    <section className={`relative min-h-screen flex items-center justify-center overflow-hidden pt-20 ${isDarkMode ? 'bg-gradient-to-br from-slate-900 via-purple-900/20 to-slate-900' : 'bg-gradient-to-br from-gray-50 to-gray-100'}`}>
      {/* Animated Background */}
      <div className="absolute inset-0 overflow-hidden">
        <motion.div 
          className="absolute -top-40 -right-40 w-80 h-80 bg-purple-500/20 rounded-full blur-3xl"
          animate={{ y: [0, 50, 0] }}
          transition={{ duration: 4, repeat: Infinity }}
        ></motion.div>
        <motion.div 
          className="absolute -bottom-40 -left-40 w-80 h-80 bg-pink-500/20 rounded-full blur-3xl"
          animate={{ y: [0, -50, 0] }}
          transition={{ duration: 4, repeat: Infinity, delay: 0.2 }}
        ></motion.div>
      </div>

      <div className="relative z-10 max-w-4xl mx-auto px-4 text-center">
        <motion.div
          initial={{ opacity: 0, scale: 0.5 }}
          animate={{ opacity: 1, scale: 1 }}
          transition={{ duration: 0.8 }}
          className="mb-8"
        >
          <div className="w-48 h-48 mx-auto mb-8 relative">
            <motion.div
              className="absolute inset-0 bg-gradient-to-br from-purple-500 to-pink-500 rounded-full blur-3xl opacity-70"
              animate={{ scale: [1, 1.15, 1] }}
              transition={{ duration: 3, repeat: Infinity }}
            ></motion.div>
            <motion.div
              className="absolute inset-0 bg-gradient-to-br from-purple-500 to-pink-500 rounded-full p-2"
              whileHover={{ scale: 1.08 }}
              transition={{ duration: 0.3 }}
            >
              <img 
                src={profileImageUrl}
                alt="Rissa Anne Gaspe"
                className="w-full h-full object-cover rounded-full border-4 border-slate-900 shadow-2xl"
                onError={(e) => {
                  e.target.style.display = 'none';
                }}
              />
            </motion.div>
          </div>
        </motion.div>

        <motion.div
          initial={{ opacity: 0, y: 20 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.2, duration: 0.8 }}
        >
          <h1 className={`text-5xl md:text-7xl font-bold mb-4 ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
            Rissa Anne Gaspe
          </h1>
        </motion.div>

        <motion.div
          initial={{ opacity: 0, y: 20 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.4, duration: 0.8 }}
          className="h-16 mb-6"
        >
          <div className="text-2xl md:text-3xl font-semibold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 via-pink-400 to-purple-400">
            <motion.span
              animate={{ opacity: [0, 1, 0] }}
              transition={{ duration: 3, repeat: Infinity, repeatDelay: 0.5 }}
            >
              Digital Solutions Architect
            </motion.span>
          </div>
        </motion.div>

        <motion.p
          initial={{ opacity: 0, y: 20 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.6, duration: 0.8 }}
          className={`text-lg md:text-xl mb-8 max-w-2xl mx-auto leading-relaxed ${isDarkMode ? 'text-gray-300' : 'text-gray-700'}`}
        >
          Transforming businesses through innovative web development, strategic automation, and cutting-edge digital solutions. With 14+ years of expertise in customer success, I blend technical mastery with business acumen.
        </motion.p>

        <motion.div
          initial={{ opacity: 0, y: 20 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.8, duration: 0.8 }}
          className="flex flex-wrap gap-4 justify-center"
        >
          <motion.button
            className="px-8 py-4 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-lg font-semibold text-lg hover:shadow-lg hover:shadow-purple-500/50 transition-all flex items-center gap-2"
            whileHover={{ scale: 1.05 }}
            whileTap={{ scale: 0.95 }}
          >
            View My Work
            <ArrowRight className="w-5 h-5" />
          </motion.button>
          <motion.button
            className={`px-8 py-4 border-2 border-purple-500 text-purple-400 rounded-lg font-semibold text-lg hover:bg-purple-500/10 transition-all flex items-center gap-2`}
            whileHover={{ scale: 1.05 }}
            whileTap={{ scale: 0.95 }}
          >
            <Download className="w-5 h-5" />
            Download Resume
          </motion.button>
        </motion.div>
      </div>

      <motion.div
        className="absolute bottom-8 left-1/2 transform -translate-x-1/2"
        animate={{ y: [0, 10, 0] }}
        transition={{ duration: 2, repeat: Infinity }}
      >
        <ChevronDown className="w-8 h-8 text-purple-400" />
      </motion.div>
    </section>
  );

  // About Section
  const AboutSection = () => (
    <section id="about" className={`py-20 px-4 ${isDarkMode ? 'bg-slate-800/50' : 'bg-gray-50'}`}>
      <div className="max-w-6xl mx-auto">
        <motion.div
          initial={{ opacity: 0, y: 20 }}
          whileInView={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.8 }}
          viewport={{ once: true }}
          className="text-center mb-16"
        >
          <h2 className={`text-4xl md:text-5xl font-bold mb-4 ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
            About Me
          </h2>
          <div className="w-20 h-1 bg-gradient-to-r from-purple-500 to-pink-500 mx-auto"></div>
        </motion.div>

        <div className="grid md:grid-cols-2 gap-12 items-center">
          <motion.div
            initial={{ opacity: 0, x: -30 }}
            whileInView={{ opacity: 1, x: 0 }}
            transition={{ duration: 0.8 }}
            viewport={{ once: true }}
            className={`${isDarkMode ? 'text-gray-300' : 'text-gray-700'} space-y-6`}
          >
            <p className="text-lg leading-relaxed">
              I'm a multifaceted professional with 14+ years of experience in customer success, digital innovation, and business technology. My journey spans from customer service excellence to strategic digital transformation.
            </p>
            <p className="text-lg leading-relaxed">
              With a degree in Nursing and training in modern tech stacks, I bring a unique blend of empathy, problem-solving, and technical expertise to every project. I'm passionate about helping businesses scale through intelligent automation, strategic marketing, and elegant web solutions.
            </p>
            <div className="pt-6 grid grid-cols-3 gap-8">
              {[
                { number: '14+', label: 'Years Experience' },
                { number: '50+', label: 'Projects Delivered' },
                { number: '20+', label: 'Skills Mastered' }
              ].map((stat, idx) => (
                <motion.div
                  key={idx}
                  initial={{ opacity: 0, scale: 0.5 }}
                  whileInView={{ opacity: 1, scale: 1 }}
                  transition={{ delay: idx * 0.1, duration: 0.6 }}
                  viewport={{ once: true }}
                  className="text-center"
                >
                  <div className="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-400">
                    {stat.number}
                  </div>
                  <p className={`text-sm mt-2 ${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
                    {stat.label}
                  </p>
                </motion.div>
              ))}
            </div>
          </motion.div>

          <motion.div
            initial={{ opacity: 0, x: 30 }}
            whileInView={{ opacity: 1, x: 0 }}
            transition={{ duration: 0.8 }}
            viewport={{ once: true }}
            className="relative"
          >
            <motion.div
              className={`p-8 rounded-2xl backdrop-blur-xl border border-purple-500/20 ${isDarkMode ? 'bg-purple-900/20' : 'bg-purple-100/20'}`}
              whileHover={{ borderColor: 'rgb(168, 85, 247)' }}
              transition={{ duration: 0.3 }}
            >
              <div className="space-y-4">
                <h3 className="text-xl font-bold text-purple-400">Key Strengths</h3>
                {[
                  'Strategic Digital Transformation',
                  'Full-Stack Web Development',
                  'Team Leadership & Management',
                  'Business Process Automation',
                  'Customer Success Excellence',
                  'Multi-platform Integration'
                ].map((strength, idx) => (
                  <motion.div
                    key={idx}
                    initial={{ opacity: 0, x: -20 }}
                    whileInView={{ opacity: 1, x: 0 }}
                    transition={{ delay: idx * 0.05 }}
                    viewport={{ once: true }}
                    className="flex items-center gap-3"
                  >
                    <div className="w-2 h-2 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full"></div>
                    <span className={isDarkMode ? 'text-gray-300' : 'text-gray-700'}>
                      {strength}
                    </span>
                  </motion.div>
                ))}
              </div>
            </motion.div>
          </motion.div>
        </div>
      </div>
    </section>
  );

  // Skills Section
  const SkillsSection = () => {
    const skillCategories = [
      {
        title: 'Web & Development',
        skills: ['WordPress', 'Elementor', 'HTML/CSS', 'Web Design', 'Squarespace'],
        color: 'from-blue-500 to-cyan-500'
      },
      {
        title: 'Business Automation',
        skills: ['Go High Level', 'Zapier', 'Make.com', 'ClickUp', 'AmorCRM'],
        color: 'from-purple-500 to-pink-500'
      },
      {
        title: 'AI & Tools',
        skills: ['Air.AI', 'ChatBot', 'Brevo', 'Overpass CRM', 'Click Up'],
        color: 'from-indigo-500 to-purple-500'
      },
      {
        title: 'E-Commerce & Platforms',
        skills: ['Shopify', 'eBay', 'Squarespace', 'Digital Marketing', 'Platform Management'],
        color: 'from-orange-500 to-red-500'
      },
      {
        title: 'Design & Marketing',
        skills: ['Photoshop', 'Graphic Design', 'Canva', 'Social Media Mgmt', 'Content Creation'],
        color: 'from-pink-500 to-rose-500'
      },
      {
        title: 'Business Management',
        skills: ['Project Management', 'Production Management', 'Talent Acquisition', 'Team Leadership', 'Cold Calling'],
        color: 'from-green-500 to-emerald-500'
      }
    ];

    return (
      <section id="skills" className={`py-20 px-4 ${isDarkMode ? 'bg-gradient-to-br from-slate-900 via-purple-900/10 to-slate-900' : 'bg-gradient-to-br from-gray-100 to-gray-50'}`}>
        <div className="max-w-6xl mx-auto">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            viewport={{ once: true }}
            className="text-center mb-16"
          >
            <h2 className={`text-4xl md:text-5xl font-bold mb-4 ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
              Skills & Expertise
            </h2>
            <p className={`text-lg ${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
              A comprehensive toolkit for modern digital solutions
            </p>
          </motion.div>

          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            {skillCategories.map((category, idx) => (
              <motion.div
                key={idx}
                initial={{ opacity: 0, y: 20 }}
                whileInView={{ opacity: 1, y: 0 }}
                transition={{ delay: idx * 0.05, duration: 0.6 }}
                viewport={{ once: true }}
                whileHover={{ y: -10 }}
                className={`p-6 rounded-xl backdrop-blur-xl border border-purple-500/20 overflow-hidden group cursor-pointer ${isDarkMode ? 'bg-slate-800/50 hover:bg-slate-800/80' : 'bg-white/50 hover:bg-white/80'} transition-all`}
              >
                <div className={`absolute inset-0 bg-gradient-to-br ${category.color} opacity-0 group-hover:opacity-10 transition-opacity duration-300`}></div>
                
                <div className="relative z-10">
                  <h3 className={`text-xl font-bold mb-4 text-transparent bg-clip-text bg-gradient-to-r ${category.color}`}>
                    {category.title}
                  </h3>
                  <div className="space-y-2">
                    {category.skills.map((skill, sidx) => (
                      <motion.div
                        key={sidx}
                        initial={{ opacity: 0, x: -10 }}
                        whileInView={{ opacity: 1, x: 0 }}
                        transition={{ delay: (idx * 0.05) + (sidx * 0.02) }}
                        viewport={{ once: true }}
                        className="flex items-center gap-2"
                      >
                        <div className={`w-2 h-2 rounded-full bg-gradient-to-r ${category.color}`}></div>
                        <span className={isDarkMode ? 'text-gray-300' : 'text-gray-700'}>
                          {skill}
                        </span>
                      </motion.div>
                    ))}
                  </div>
                </div>
              </motion.div>
            ))}
          </div>
        </div>
      </section>
    );
  };

  // Experience Section
  const ExperienceSection = () => {
    const experiences = [
      {
        title: 'Production Manager',
        company: 'Scale Strategy Group',
        period: 'October 2023 - April 2024',
        description: 'Managed production operations, staff coordination, and email marketing campaigns using Go High Level and Click Up'
      },
      {
        title: 'Recruiting Specialist',
        company: 'JCSI',
        period: 'September 2021 - October 2023',
        description: 'Conducted candidate screening and interviews, booking appointment schedules and managing recruitment workflow'
      },
      {
        title: 'Appointment Setter & Cold Caller',
        company: 'Scale Strategy Group',
        period: 'September 2021 - October 2023',
        description: 'Outbound calling for B2B lead generation with high conversion rates for enterprise clients'
      },
      {
        title: 'Digital Marketing Specialist',
        company: 'Advisor Fuel',
        period: 'January 2020 - 2021',
        description: 'Lead generation, appointment setting, and strategic email marketing campaigns'
      },
      {
        title: 'Social Media Manager & Executive VA',
        company: 'Breakthrough Social',
        period: 'November 2019 - February 2020',
        description: 'Managed 10+ social media accounts, Shopify operations, and influencer outreach for e-commerce growth'
      },
      {
        title: 'ESL Online Educator',
        company: '51Talk',
        period: 'May 2018 - March 2019',
        description: 'English language instruction to international students with focus on student engagement and performance'
      }
    ];

    return (
      <section id="experience" className={`py-20 px-4 ${isDarkMode ? 'bg-slate-800/50' : 'bg-gray-50'}`}>
        <div className="max-w-4xl mx-auto">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            viewport={{ once: true }}
            className="text-center mb-16"
          >
            <h2 className={`text-4xl md:text-5xl font-bold mb-4 ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
              Professional Experience
            </h2>
          </motion.div>

          <div className="relative">
            {/* Timeline Line */}
            <div className="absolute left-4 md:left-1/2 top-0 bottom-0 w-1 bg-gradient-to-b from-purple-500 via-pink-500 to-purple-500 md:transform md:-translate-x-1/2"></div>

            {/* Timeline Items */}
            <div className="space-y-8">
              {experiences.map((exp, idx) => (
                <motion.div
                  key={idx}
                  initial={{ opacity: 0, x: idx % 2 === 0 ? -30 : 30 }}
                  whileInView={{ opacity: 1, x: 0 }}
                  transition={{ duration: 0.6 }}
                  viewport={{ once: true }}
                  className={`relative pl-20 md:pl-0 ${idx % 2 === 0 ? 'md:pr-1/2 md:text-right' : 'md:pl-1/2 md:ml-auto'}`}
                >
                  {/* Timeline Dot */}
                  <motion.div
                    className="absolute left-0 md:left-1/2 top-2 w-8 h-8 bg-gradient-to-br from-purple-500 to-pink-500 rounded-full border-4 border-slate-900 md:transform md:-translate-x-4 flex items-center justify-center"
                    whileHover={{ scale: 1.2 }}
                  >
                    <div className="w-3 h-3 bg-slate-900 rounded-full"></div>
                  </motion.div>

                  {/* Content Card */}
                  <motion.div
                    className={`p-6 rounded-lg backdrop-blur-xl border border-purple-500/20 ${isDarkMode ? 'bg-slate-800/70 hover:bg-slate-700/70' : 'bg-white/70 hover:bg-white'} transition-all`}
                    whileHover={{ y: -5 }}
                  >
                    <h3 className="text-xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-400">
                      {exp.title}
                    </h3>
                    <p className={`text-sm mt-1 ${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
                      {exp.company}
                    </p>
                    <p className={`text-xs mt-2 ${isDarkMode ? 'text-gray-500' : 'text-gray-500'}`}>
                      {exp.period}
                    </p>
                    <p className={`mt-4 ${isDarkMode ? 'text-gray-300' : 'text-gray-700'}`}>
                      {exp.description}
                    </p>
                  </motion.div>
                </motion.div>
              ))}
            </div>
          </div>
        </div>
      </section>
    );
  };

  // Projects Section
  const ProjectsSection = () => {
    const projects = [
      {
        title: 'HR Performance Dashboard',
        description: 'Built comprehensive recruitment analytics dashboard with real-time KPIs and team leaderboards',
        tech: ['Go High Level', 'Pipedream', 'JSONBin', 'API Integration'],
        image: '📊'
      },
      {
        title: 'E-Commerce Management Platform',
        description: 'Managed 10+ social media accounts and Shopify stores with integrated inventory system',
        tech: ['Shopify', 'Social Media', 'Content Strategy', 'Growth Hacking'],
        image: '🛍️'
      },
      {
        title: 'Lead Generation System',
        description: 'Developed automated lead generation pipeline with appointment scheduling integration',
        tech: ['ClickUp', 'Go High Level', 'Automation', 'CRM'],
        image: '🎯'
      },
      {
        title: 'Website Development & Design',
        description: 'Created professional websites using WordPress, Elementor, and Squarespace',
        tech: ['WordPress', 'Elementor', 'Web Design', 'UX/UI'],
        image: '🌐'
      },
      {
        title: 'Marketing Automation Campaign',
        description: 'Strategic email marketing and SMS campaigns with personalized automation workflows',
        tech: ['Brevo', 'Email Marketing', 'SMS', 'Zapier'],
        image: '✉️'
      },
      {
        title: 'Content Management System',
        description: 'Developed and managed multiple content calendars and social media strategies',
        tech: ['Canva', 'Content Strategy', 'Scheduling', 'Analytics'],
        image: '📱'
      }
    ];

    return (
      <section id="projects" className={`py-20 px-4 ${isDarkMode ? 'bg-gradient-to-br from-slate-900 via-purple-900/10 to-slate-900' : 'bg-gradient-to-br from-gray-100 to-gray-50'}`}>
        <div className="max-w-6xl mx-auto">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            viewport={{ once: true }}
            className="text-center mb-16"
          >
            <h2 className={`text-4xl md:text-5xl font-bold mb-4 ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
              Featured Projects
            </h2>
          </motion.div>

          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            {projects.map((project, idx) => (
              <motion.div
                key={idx}
                initial={{ opacity: 0, y: 20 }}
                whileInView={{ opacity: 1, y: 0 }}
                transition={{ delay: idx * 0.05, duration: 0.6 }}
                viewport={{ once: true }}
                whileHover={{ y: -10 }}
                className={`group relative rounded-xl overflow-hidden backdrop-blur-xl border border-purple-500/20 h-80 cursor-pointer`}
              >
                {/* Background */}
                <div className={`absolute inset-0 ${isDarkMode ? 'bg-gradient-to-br from-slate-800/80 to-slate-700/80' : 'bg-gradient-to-br from-white/80 to-gray-50/80'}`}></div>
                
                {/* Animated Gradient on Hover */}
                <motion.div
                  className="absolute inset-0 bg-gradient-to-br from-purple-500/20 to-pink-500/20 opacity-0 group-hover:opacity-100 transition-opacity duration-300"
                ></motion.div>

                {/* Content */}
                <div className="relative z-10 p-6 h-full flex flex-col">
                  <div className="text-5xl mb-4">{project.image}</div>
                  <h3 className="text-xl font-bold text-white mb-2">
                    {project.title}
                  </h3>
                  <p className={`text-sm flex-grow ${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
                    {project.description}
                  </p>
                  <div className="flex flex-wrap gap-2 mt-4">
                    {project.tech.map((t, tidx) => (
                      <span
                        key={tidx}
                        className="px-2 py-1 text-xs rounded bg-purple-500/30 text-purple-300 border border-purple-500/50"
                      >
                        {t}
                      </span>
                    ))}
                  </div>
                </div>
              </motion.div>
            ))}
          </div>
        </div>
      </section>
    );
  };

  // Services Section
  const ServicesSection = () => {
    const services = [
      {
        title: 'Web Development',
        description: 'Custom websites and e-commerce platforms using modern technologies',
        icon: '💻'
      },
      {
        title: 'Business Automation',
        description: 'Streamline operations with Go High Level, Zapier, and Make integrations',
        icon: '⚙️'
      },
      {
        title: 'Digital Marketing',
        description: 'Email campaigns, social media management, and growth strategies',
        icon: '📈'
      },
      {
        title: 'Graphic Design',
        description: 'Professional branding, graphics, and visual content creation',
        icon: '🎨'
      },
      {
        title: 'CRM Solutions',
        description: 'Implementation and optimization of customer relationship systems',
        icon: '👥'
      },
      {
        title: 'AI Integration',
        description: 'Implement AI tools and chatbots for enhanced customer experience',
        icon: '🤖'
      }
    ];

    return (
      <section id="services" className={`py-20 px-4 ${isDarkMode ? 'bg-slate-800/50' : 'bg-gray-50'}`}>
        <div className="max-w-6xl mx-auto">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            viewport={{ once: true }}
            className="text-center mb-16"
          >
            <h2 className={`text-4xl md:text-5xl font-bold mb-4 ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
              Services I Offer
            </h2>
          </motion.div>

          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            {services.map((service, idx) => (
              <motion.div
                key={idx}
                initial={{ opacity: 0, scale: 0.9 }}
                whileInView={{ opacity: 1, scale: 1 }}
                transition={{ delay: idx * 0.05, duration: 0.6 }}
                viewport={{ once: true }}
                whileHover={{ y: -5 }}
                className={`p-8 rounded-xl backdrop-blur-xl border border-purple-500/20 group overflow-hidden ${isDarkMode ? 'bg-slate-800/70' : 'bg-white/70'}`}
              >
                <motion.div
                  className="absolute inset-0 bg-gradient-to-br from-purple-500/20 to-pink-500/20 opacity-0 group-hover:opacity-100 transition-opacity duration-300"
                ></motion.div>
                
                <div className="relative z-10">
                  <div className="text-5xl mb-4">{service.icon}</div>
                  <h3 className="text-xl font-bold mb-3 text-white">
                    {service.title}
                  </h3>
                  <p className={isDarkMode ? 'text-gray-400' : 'text-gray-600'}>
                    {service.description}
                  </p>
                </div>
              </motion.div>
            ))}
          </div>
        </div>
      </section>
    );
  };

  // Contact Section
  const ContactSection = () => (
    <section id="contact" className={`py-20 px-4 ${isDarkMode ? 'bg-gradient-to-br from-slate-900 via-purple-900/10 to-slate-900' : 'bg-gradient-to-br from-gray-100 to-gray-50'}`}>
      <div className="max-w-4xl mx-auto">
        <motion.div
          initial={{ opacity: 0, y: 20 }}
          whileInView={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.8 }}
          viewport={{ once: true }}
          className="text-center mb-16"
        >
          <h2 className={`text-4xl md:text-5xl font-bold mb-4 ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
            Let's Connect
          </h2>
          <p className={`text-lg ${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
            Ready to discuss your next project or opportunity
          </p>
        </motion.div>

        <div className="grid md:grid-cols-2 gap-8 mb-12">
          {[
            { icon: Mail, label: 'Email', value: 'purplepinkcotton@gmail.com', link: 'mailto:purplepinkcotton@gmail.com' },
            { icon: Phone, label: 'Phone', value: '+63 953 854 7179', link: 'tel:+639538547179' }
          ].map((contact, idx) => (
            <motion.a
              key={idx}
              href={contact.link}
              initial={{ opacity: 0, y: 20 }}
              whileInView={{ opacity: 1, y: 0 }}
              transition={{ delay: idx * 0.1, duration: 0.6 }}
              viewport={{ once: true }}
              whileHover={{ scale: 1.05 }}
              className={`p-6 rounded-xl backdrop-blur-xl border border-purple-500/20 group overflow-hidden ${isDarkMode ? 'bg-slate-800/70 hover:bg-slate-800/90' : 'bg-white/70 hover:bg-white'} transition-all`}
            >
              <motion.div className="absolute inset-0 bg-gradient-to-br from-purple-500/20 to-pink-500/20 opacity-0 group-hover:opacity-100 transition-opacity duration-300"></motion.div>
              
              <div className="relative z-10 flex items-center gap-4">
                <div className="p-3 rounded-lg bg-gradient-to-br from-purple-500/30 to-pink-500/30">
                  <contact.icon className="w-6 h-6 text-purple-400" />
                </div>
                <div>
                  <p className={`text-sm ${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
                    {contact.label}
                  </p>
                  <p className="text-lg font-semibold text-white">
                    {contact.value}
                  </p>
                </div>
              </div>
            </motion.a>
          ))}
        </div>

        {/* Social Links */}
        <motion.div
          initial={{ opacity: 0, y: 20 }}
          whileInView={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.2, duration: 0.6 }}
          viewport={{ once: true }}
          className="flex justify-center gap-6 mb-12"
        >
          {[
            { icon: Linkedin, label: 'LinkedIn', link: '#' },
            { icon: Github, label: 'GitHub', link: '#' },
            { icon: Mail, label: 'Email', link: 'mailto:purplepinkcotton@gmail.com' }
          ].map((social, idx) => (
            <motion.a
              key={idx}
              href={social.link}
              target="_blank"
              rel="noopener noreferrer"
              className={`p-4 rounded-full backdrop-blur-xl border border-purple-500/20 ${isDarkMode ? 'bg-slate-800/50 hover:bg-slate-800/80' : 'bg-white/50 hover:bg-white'} transition-all`}
              whileHover={{ scale: 1.15, y: -5 }}
              whileTap={{ scale: 0.95 }}
            >
              <social.icon className="w-6 h-6 text-purple-400" />
            </motion.a>
          ))}
        </motion.div>

        {/* Contact Form */}
        <motion.form
          initial={{ opacity: 0, y: 20 }}
          whileInView={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.3, duration: 0.6 }}
          viewport={{ once: true }}
          className={`p-8 rounded-xl backdrop-blur-xl border border-purple-500/20 ${isDarkMode ? 'bg-slate-800/70' : 'bg-white/70'}`}
        >
          <div className="grid md:grid-cols-2 gap-6 mb-6">
            <input
              type="text"
              placeholder="Your Name"
              className={`px-4 py-3 rounded-lg backdrop-blur-xl border border-purple-500/20 ${isDarkMode ? 'bg-slate-900/50 text-white placeholder-gray-500' : 'bg-gray-100 text-gray-900 placeholder-gray-500'} focus:outline-none focus:border-purple-500/50 focus:ring-2 focus:ring-purple-500/20 transition-all`}
            />
            <input
              type="email"
              placeholder="Your Email"
              className={`px-4 py-3 rounded-lg backdrop-blur-xl border border-purple-500/20 ${isDarkMode ? 'bg-slate-900/50 text-white placeholder-gray-500' : 'bg-gray-100 text-gray-900 placeholder-gray-500'} focus:outline-none focus:border-purple-500/50 focus:ring-2 focus:ring-purple-500/20 transition-all`}
            />
          </div>
          <textarea
            placeholder="Your Message"
            rows="5"
            className={`w-full px-4 py-3 rounded-lg backdrop-blur-xl border border-purple-500/20 ${isDarkMode ? 'bg-slate-900/50 text-white placeholder-gray-500' : 'bg-gray-100 text-gray-900 placeholder-gray-500'} focus:outline-none focus:border-purple-500/50 focus:ring-2 focus:ring-purple-500/20 transition-all resize-none`}
          ></textarea>
          <motion.button
            type="submit"
            className="mt-6 w-full px-8 py-3 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-lg font-semibold hover:shadow-lg hover:shadow-purple-500/50 transition-all"
            whileHover={{ scale: 1.02 }}
            whileTap={{ scale: 0.98 }}
          >
            Send Message
          </motion.button>
        </motion.form>
      </div>
    </section>
  );

  // Footer
  const Footer = () => (
    <motion.footer
      initial={{ opacity: 0 }}
      whileInView={{ opacity: 1 }}
      transition={{ duration: 0.8 }}
      viewport={{ once: true }}
      className={`py-8 px-4 border-t border-purple-500/20 ${isDarkMode ? 'bg-slate-900/50' : 'bg-gray-100/50'}`}
    >
      <div className="max-w-6xl mx-auto text-center">
        <p className={`${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
          © 2024 Rissa Anne Gaspe. All rights reserved.
        </p>
        <p className={`text-sm mt-2 ${isDarkMode ? 'text-gray-500' : 'text-gray-700'}`}>
          Crafted with passion | Designed for excellence
        </p>
      </div>
    </motion.footer>
  );

  return (
    <div className={`min-h-screen transition-colors duration-500 ${isDarkMode ? 'bg-slate-900 text-white' : 'bg-gray-50 text-gray-900'}`}>
      <NavBar />
      <HeroSection />
      <AboutSection />
      <SkillsSection />
      <ExperienceSection />
      <ProjectsSection />
      <ServicesSection />
      <ContactSection />
      <Footer />
    </div>
  );
};

export default Portfolio;

#   E m p l o y e e s   P a y r o l l  
  
 # #   S u b m o d u l e  
  
 *   A   s u b m o d u l e   r e f e r e n c e s   a   s p e c i f i c   c o m m i t   i n   a n o t h e r   r e p o s i t o r y .  
  
 # #   A d d   S u b m o d u l e  
  
 Y o u   c a n   i n c l u d e   a n o t h e r   G i t   r e p o s i t o r y   a s   a   f o l d e r   w i t h i n   y o u r   p r o j e c t ,   t r a c k e d   b y   G i t  
  
 ` ` ` s h e l l  
 g i t   s u b m o d u l e   a d d   < u r l _ r e p o s i t o r y >  
 ` ` `  
  
 # #   I n i t   s u b m o d u l e  
  
 ` ` ` s h e l l  
 c d   m o d u l e  
  
 #   I n i t   l o c a l   c o n f i g u r a t i o n  
 g i t   s u b m o d u l e   i n i t  
  
 #   F i n d   a l l   t h e   d a t a   f o r   t h a t   p r o j e c t   a n d   c h e c k   f o r   t h e   p r o p e r   c o m m i t   i n   y o u r   s u p e r p r o j e c t    
 g i t   s u b m o d u l e   u p d a t e  
  
 ` ` `  
  
 # #   P u l l   a l l   s u b m o d u l e s  
  
 ` ` ` s h e l l  
 #   C o n f i g u r a c i � n  
 g i t   c o n f i g   s u b m o d u l e . r e c u r s e   t r u e  
 g i t   p u l l   - - r e c u r s e - s u b m o d u l e s  
  
 #   T o   c h e c k   o u t   a l l   s u b m o d u l e s   t o   t h e   l a t e s t   s t a t e   o n   t h e   r e m o t e  
 g i t   s u b m o d u l e   f o r e a c h   g i t   p u l l   < r e m o t e >   < b r a n c h >  
  
 #   T o   c h e c k o u t   t h e   l a t e s t   s t a t e   o f   a   s p e c i f i c   s u b m o d u l e  
 g i t   s u b m o d u l e   u p d a t e   - - r e m o t e   < s u b m o d u l e _ d i r e c t o r y >  
  
 #     C a n   r e q u e s t   t o   u p d a t e   t h a t   s u b m o d u l e   t o   t h e   l a t e s t   c o m m i t   o f   a   b r a n c h   o f   t h e   s u b m o d u l e   r e m o t e   r e p o  
 g i t   s u b m o d u l e   u p d a t e   - - r e m o t e   - - r e c u r s i v e  
 ` ` `  
  
 # #   C l o n e   p r o j e c t  
  
 W a y s   t o   c l o n e   t h e   w h o l e   p r o j e c t .  
  
 # # #   1   C l o n e   p r o j e c t   a f t e r   t h e   s u b m o d u l e s  
  
 ` ` ` s h e l l  
 g i t   c l o n e   u r _ r o o t _ p r o j e c t  
 c d   u r l _ r o o t _ p r o j e c t  
 g i t   s u b m o d u l e   u p d a t e   - - i n i t  
 ` ` `  
  
 # # #   2   C l o n i n g     t o   i n i t i a l i z e   a n d   u p d a t e   s u b m o d u l e s  
  
 ` ` ` s h e l l  
 g i t   c l o n e   - - r e c u r s i v e   u r l _ r o o t _ p r o j e c t  
 ` ` `  
  
 # # #   T o   c h e c k   o u t   t h e   e x a c t   s t a t e   t h a t   i s   r e f e r e n c e d   f o r   a l l   s u b m o d u l e s  
  
 ` ` ` s h e l l  
 g i t   s u b m o d u l e   u p d a t e   - - r e c u r s i v e  
 ` ` `  
  
 # #     R e m o v i n g   a   s u b m o d u l e  
  
 ` ` ` s h e l l  
 g i t   s u b m o d u l e   d e i n i t   t h e _ s u b m o d u l e  
 g i t   r m   t h e _ s u b m o d u l e  
 ` ` `  
  
 
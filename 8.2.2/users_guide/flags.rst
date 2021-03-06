..
   .. _flag-reference:

   Flag reference
   ==============

   This section is a quick-reference for GHC's command-line flags. For each
   flag, we also list its static/dynamic status (see
   :ref:`static-dynamic-flags`), and the flag's opposite (if available).

.. _flag-reference:

フラグの一覧表
==============

このセクションは GHC のコマンドラインフラグの早見表です．
それぞれのフラグについて，動的/静的の区別(:ref:`static-dynamic-flags` 参照)と逆のフラグ(存在すれば)も載せています．

..
   Verbosity options
   -----------------

   More details in :ref:`options-help`

   .. include:: flags-verbosity.gen.rst

饒舌性に関するオプション
------------------------

より詳しくは :ref:`options-help` にあります．

.. include:: flags-verbosity.gen.rst

..
   Alternative modes of operation
   ------------------------------

   More details in :ref:`modes`

   .. include:: flags-modes.gen.rst

通常以外の実行モード
--------------------

より詳しくは :ref:`modes` にあります．

.. include:: flags-modes.gen.rst

..
   Which phases to run
   -------------------

   More details in :ref:`options-order`

   .. include:: flags-phases.gen.rst

どの段階を実行するか
--------------------

より詳しくは :ref:`options-order` にあります．

.. include:: flags-phases.gen.rst

..
   Redirecting output
   ------------------

   More details in :ref:`options-output`

   .. include:: flags-redirecting-output.gen.rst

出力先の変更
------------

より詳しくは :ref:`options-output` にあります．

.. include:: flags-redirecting-output.gen.rst

..
   Keeping intermediate files
   --------------------------

   More details in :ref:`keeping-intermediates`

   .. include:: flags-keeping-intermediates.gen.rst

中間ファイルの保持
------------------

より詳しくは :ref:`keeping-intermediates` にあります．

.. include:: flags-keeping-intermediates.gen.rst

..
   Temporary files
   ---------------

   More details in :ref:`temp-files`

   .. include:: flags-temporary-files.gen.rst

一時ファイル
------------

より詳しくは :ref:`temp-files` にあります．

.. include:: flags-temporary-files.gen.rst

..
   Finding imports
   ---------------

   More details in :ref:`search-path`

   .. include:: flags-finding-imports.gen.rst

インポートの検索
----------------

詳しくは :ref:`search-path` にあります．

.. include:: flags-finding-imports.gen.rst

..
   Interface file options
   ----------------------

   More details in :ref:`hi-options`

   .. include:: flags-interface-files.gen.rst

インターフェイスファイル関連オプション
--------------------------------------

詳しくは :ref:`hi-options` にあります．

.. include:: flags-interface-files.gen.rst

..
   Recompilation checking
   ----------------------

   More details in :ref:`recomp`

   .. include:: flags-recompilation-checking.gen.rst

   .. _interactive-mode-options:

再コンパイル検査
----------------

詳しくは :ref:`recomp` にあります．

.. include:: flags-recompilation-checking.gen.rst

.. _interactive-mode-options:

..
   Interactive-mode options
   ------------------------

   More details in :ref:`ghci-dot-files`

   .. include:: flags-interactive.gen.rst

対話モードのオプション
----------------------

詳しくは :ref:`ghci-dot-files` にあります．

.. include:: flags-interactive.gen.rst

..
   Packages
   --------

   More details in :ref:`packages`

   .. include:: flags-packages.gen.rst

パッケージ
----------

詳しくは :ref:`packages` にあります．

.. include:: flags-packages.gen.rst

..
   Language options
   ----------------

   Language options can be enabled either by a command-line option
   ``-Xblah``, or by a ``{-# LANGUAGE blah #-}`` pragma in the file itself.
   See :ref:`options-language`. Some options are enabled using ``-f*``
   flags.

   .. include:: flags-language.gen.rst

言語オプション
--------------

言語オプションを有効にするには ``-Xなんたら`` というコマンドラインオプションを使うか，
プログラムファイルで ``{-# LANGUAGE blah #-}`` プラグマを使います．
:ref:`options-language` 参照． いくつかのオプションについては ``-f*`` を使うと有効になります．

.. include:: flags-language.gen.rst

..
   Warnings
   --------

   More details in :ref:`options-sanity`

   .. include:: flags-warnings.gen.rst

警告
----

詳しくは :ref:`options-sanity` にあります．

.. include:: flags-warnings.gen.rst

..
   Optimisation levels
   -------------------

   These options are described in more detail in :ref:`options-optimise`.

   See :ref:`options-f-compact` for a list of optimisations enabled on
   level 1 and level 2.

   .. include:: flags-optimization-levels.gen.rst

最適化レベルの設定
------------------

これらのオプションについて詳しくは :ref:`options-optimise` にあります．

レベル 1 およびレベル 2 で有効になる最適化一覧については :ref:`options-f-compact` を参照してください．

.. include:: flags-optimization-levels.gen.rst

..
   .. _options-f-compact:

   Individual optimisations
   ------------------------

   These options are described in more detail in :ref:`options-f`. If a
   flag is implied by ``-O`` then it is also implied by ``-O2`` (unless
   flag description explicitly says otherwise). If a flag is implied by
   ``-O0`` only then the flag is not implied by ``-O`` and ``-O2``.

   .. include:: flags-optimization.gen.rst

.. _options-f-compact:

個々の最適化
------------

これらのオプションについてより詳しくは :ref:`options-f` にあります．
``-O`` で有効になるフラグは(別指定をしないかぎり) ``-O2`` ででも有効になります．
``-O0`` で有効になるフラグについては，``-O`` や ``-O2`` を指定しても有効にはなりません．

.. include:: flags-optimization.gen.rst

..
   Profiling options
   -----------------

   More details in :ref:`profiling`

   .. include:: flags-profiling.gen.rst

プロファイリングオプション
--------------------------

詳しくは :ref:`profiling` にあります．

.. include:: flags-profiling.gen.rst

..
   Program coverage options
   ------------------------

   More details in :ref:`hpc`

   .. include:: flags-program-coverage.gen.rst

プログラム網羅オプション
------------------------

より詳しくは :ref:`hpc` にあります．

.. include:: flags-program-coverage.gen.rst

..
   C pre-processor options
   -----------------------

   More details in :ref:`c-pre-processor`

   .. include:: flags-cpp.gen.rst

C プリプロセッサオプション
--------------------------

より詳しくは :ref:`c-pre-processor` にあります．

.. include:: flags-cpp.gen.rst

..
   Code generation options
   -----------------------

   More details in :ref:`options-codegen`

   .. include:: flags-codegen.gen.rst

コード生成オプション
----------------------------

より詳しくは :ref:`options-codegen` にあります．

.. include:: flags-codegen.gen.rst

..
   Linking options
   ---------------

   More details in :ref:`options-linker`

   .. include:: flags-linking.gen.rst

リンクオプション
----------------

より詳しくは :ref:`options-linker` にあります．

.. include:: flags-linking.gen.rst

..
   Plugin options
   --------------

   More details in :ref:`compiler-plugins`

   .. include:: flags-plugin.gen.rst

プラグインオプション
--------------------

より詳しくは :ref:`compiler-plugins` にあります．

.. include:: flags-plugin.gen.rst

..
   Replacing phases
   ----------------

   More details in :ref:`replacing-phases`

   .. include:: flags-phase-programs.gen.rst

   .. index::
      single: -pgmL
      single: -pgmP
      single: -pgmc
      single: -pgmlo
      single: -pgmlc
      single: -pgma
      single: -pgml
      single: -pgmdll
      single: -pgmF

フェーズの置き換え
------------------

より詳しくは :ref:`replacing-phases` にあります．

.. include:: flags-phase-programs.gen.rst

.. index::
   single: -pgmL
   single: -pgmP
   single: -pgmc
   single: -pgmlo
   single: -pgmlc
   single: -pgma
   single: -pgml
   single: -pgmdll
   single: -pgmF

..
   Forcing options to particular phases
   ------------------------------------

   More details in :ref:`forcing-options-through`

   .. include:: flags-phase-specific.gen.rst

特定のフェーズにオプションを渡す
--------------------------------

より詳しくは :ref:`forcing-options-through` にあります．

.. include:: flags-phase-specific.gen.rst

..
   Platform-specific options
   -------------------------

   More details in :ref:`options-platform`

   .. include:: flags-platform-specific.gen.rst

プラットフォーム固有のオプション
--------------------------------

詳しくは :ref:`options-platform` にあります．

.. include:: flags-platform-specific.gen.rst

..
   Compiler debugging options
   --------------------------

   More details in :ref:`options-debugging`

   .. include:: flags-compiler-debugging.gen.rst

コンパイラをデバッグするためのオプション
----------------------------------------

より詳しくは :ref:`options-debugging` にあります．

.. include:: flags-compiler-debugging.gen.rst

..
   Miscellaneous compiler options
   ------------------------------

   .. include:: flags-misc.gen.rst

その他のコンパイルオプション
----------------------------

.. include:: flags-misc.gen.rst

